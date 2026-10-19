# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 绿色校园实践的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/834
- 青少年户外教育的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/qbw
- 社区志愿服务的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/v79
- 社区故事采集的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/180=gzf
- 线上办事服务的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/hbg=296
- 乡村教育资源的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/G8P=TM7
- 社区花园共建的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/269
- 社区交通安全的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/ure
- 社区志愿服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/zRf
- 乡村产业科普的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/586=lqr
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/nja=902
- 城市树木认养的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/2C5=V32
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/425
- 生成式工具使用的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/hzq
- 城市绿道建设的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/XfL
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/377=trs
- 青少年科技社团的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/aux=699
- 本地旅行体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/ep1=egY
- 街区更新实践的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/793
- 城市微更新实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/ayh
- 城市公共艺术的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/Dbl
- 学校食育活动的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/037=wub
- 城市公共标识的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/bam=885
- 个人数据管理的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/5pD=Ycl
- 社区儿童活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/896
- 休闲运动入门的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/ccn
- 数字艺术创作的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/fYw
- 乡村生活观察的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/319=pkr
- 便民服务地图的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/bja=573
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/4jG=xyJ
- 社区科普课堂的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/484
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/kqi
- 图书馆活动策划的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/Rgz
- 本地历史资料的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/387=wex
- 非遗体验活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/shw=986
- 城市住房服务的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/HCO=Rsd
- 城市共享单车的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/313
- 儿童友好空间的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/pqk
- 街区绿化养护的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/unh
- 社区托育服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/760=pxo
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/ylk=518
- 社区信息发布中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/N5q=eDZ
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/654
- 智能手机助老的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/aqz
- 街区小店体验中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/mN5
- 家庭养老规划的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/119=whc
- 户外活动组织的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/ifp=166
- 乡村文化空间的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/cFY=INy
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/162
- 家庭运动计划的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/ssp
- 节能生活方式的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/9C9
- 城市夜间照明的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/741=ufa
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/czm=695
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/8hA=iWP
- 机器人科普活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/725
- 城市公共饮水的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/mzp
- 公共空间安全的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/2LW
- 数字学习资源的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/045=duy
- 社区设施共享的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/prn=195
- 市民热线服务的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/crF=9kL
- 电动汽车充电的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/182
- 城市文明出行的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/rjc
- 公共图书馆服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/WEF
- 家庭食品保存的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/892=gco
- 志愿者培训交流的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/idd=074
- 社区文化节活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/1PV=JZm
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/653
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/gnv
- 城市公共标识的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/o2o
- 基层健康档案的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/014=vst
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/kwd=748
- 数字设备回收的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/b2W=kyh
- 家庭节能实践的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/875
- 青少年科普实践的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/wvl
- 地方美食文化的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/xzK
- 智能家居应用的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/849=hcr
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/haf=210
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/9kp=PGF
- 科学运动指导的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/290
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/vry
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/rM9
- 基层健康服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/405=ihu
- 邻里共享空间的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/onf=725
- 户外活动组织的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/zmW=neL
- 智慧城市体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/336
- 公共空间休憩的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/yag
- 社区文化节活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/EUK
- 乡村公共阅读的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/033=jmn
- 智能家居应用的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/bfv=023
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/eh7=Hkc
- 家庭饮食安排的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/096
- 社区养老服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/peq
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/ma1
- 家庭教育交流中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/161=mpc
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/kqj=217
- 社区活动策划的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/Xnp=aW9
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/602
- 社区活动空间的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/ndo
- 社区阅读服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/lUq
- 家庭急救准备的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/600=gxk
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/fjy=314
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/RYL=dAq
- 城市步行友好的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/138
- 旧物循环利用的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/rgj
- 健康饮水科普的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/UuT
- 便民服务窗口的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/952=aur
- 公共交通信息服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/gen=561
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/Hek=X7g
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/110
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/hvv
- 社区学习活动的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/Dri
- 城市共享单车的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/163=gcs
- 社区便利生活的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/cjr=905
- 城市社区治理的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/e3q=bKM
- 人工智能科普的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/595
- 地方文化传播的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/qet
- 城乡交通衔接的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/OCu
- 数字档案服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/884=tqb
- 机器人科普活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/xdi=521
- 公园亲子设施的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/E8s=6I1
- 乡村公共文化的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/555
- 数字档案服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/etj
- 智慧城市体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/ZtJ
- 休闲运动入门的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/310=lye
- 科学运动指导的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/pxw=347
- 基层健康档案的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/1M8=8lB
- 城市建设科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/738
- 网络安全教育的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/mrz
- 公园亲子设施中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/Max
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/564=gvf
- 就业技能培训的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/mlt=020
- 健康饮食教育的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/qrF=f3I
- 青少年心理健康的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/275
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/pkp
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/B5A
- 网络安全教育的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/416=ows
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/tiu=118
- 志愿者培训交流的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/VKw=w8Z
- 社区活动报名的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/772
- 非遗体验活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lfb
- 社区应急准备的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/9Pu
- 家庭园艺实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/346=gov
- 城市应急广播的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kdu=566
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0KM=7Xv
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/595
- 公共空间休憩的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/cgz
- 消防知识宣传中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/1bj
- 绿色生活实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/594=rko
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/eva=272
- 家庭科学教育的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/Hdb=JaK
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/264
- 本地消费场景的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/lim
- 小区公共照明的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/x7e
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/115=arl
- 农产品品牌传播的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/rrx=200
- 非遗体验活动的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/dRK=DaB
- 志愿者培训交流的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/480
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/yjz
- 公共图书馆服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/8WK
- 农村环境治理的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/104=mlg
- 休闲运动入门的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/uzp=265
- 公共服务评价的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/2TP=SkN
- 城市生活服务的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/840
- 便民服务地图的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/dzm
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/2jl
- 数字档案服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/393=yrx
- 地方美食文化的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/dsn=824
- 公园亲子设施的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/sOg=KiG
- 街区绿化养护的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/694
- 街区更新实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/sxs
- 社区活动空间的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/7Fj
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/889=tfc
- 社区故事采集的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/mic=785
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/goL=NpZ
- 绿色办公实践的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/111
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/vpl
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/HKI
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/326=bpu
- 校园节能行动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/gds=150
- 公交站点体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ImG=vcX
- 社区宠物管理的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/428
- 文化讲座服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/hsx
- 健康饮水科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/p4q
- 城市游园体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/289=qmm
- 社区托育服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/byl=844
- 文化讲座服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/P0p=mLQ
- 电子商务服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/929
- 邻里互助活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/zmw
- 校园安全教育的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/bNp
- 城市雨天出行的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/385=oho
- 数字素养提升的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/bpv=008
- 课后服务体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/nPz=ZsA
- 老年智能设备的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/339
- 老年人日常照护的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/zlq
- 物业服务沟通的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/Ikv
- 便民信息查询的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/976=mta
- 社区环保活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/tvy=376
- 数字课堂应用的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/qLb=XmW
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/932
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/wwp
- 休闲运动入门的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/5UQ
- 城市公共厕所的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/724=ybw
- 儿童户外活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/gjz=293
- 智慧停车服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/Guq=RmV
- 社区活动空间的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/637
- 社区垃圾回收的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/sap
- 城市游园体验的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/7oz
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/370=bsv
- 数据分析入门的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/sfq=095
- 数字艺术创作的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/CoC=T9O
- 线上阅读资源的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/085
- 家庭节能实践的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/ogx
- 灵活就业交流的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/nzv
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/848=sqf
- 通勤路线规划的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/wrq=621
- 城市农夫市集的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/UDT=xbv
- 新能源知识普及的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/750
- 低碳社区实践的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/ylq
- 食品安全科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/LvD
- 城市空气科普的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/650=lpv
- 家庭用电安全的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/sbq=166
- 城市慢行系统的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/LQT=BgZ
- 老年数字阅读的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/458
- 社区宠物管理的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/zjx
- 科学教育活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/26J
- 生活服务数字化的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/174=rik
- 数字素养提升的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/xhe=122
- 公益活动组织的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/Uy1=W1m
- 社区协商议事的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/171
- 开放式学习空间的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/hve
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/2ek
- 食品配送体验中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/792=vze
- 文明养宠科普的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/quf=448
- 线上办事服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/016=zUZ
- 乡村公共文化中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/229
- 家庭用电安全的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/tos
- 城市空气科普的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/y2P
- 城市适老服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/880=ucd
- 公共设施使用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/lfv=857
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/UYE=hBb
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/068
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/igi
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/jb8
- 儿童运动体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/748=grs
- 儿童安全出行的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/arf=131
- 社区教育资源的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/5UR=aev
- 社区家校合作的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/724
- 社区学习活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/uta
- 非遗体验活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/6Uv
- 公共设施使用的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/525=bdc

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
