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

- 公共健身器材从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/7g0
- 家庭养老规划的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/434=fzx
- 社区家校合作的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/uvs=717
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/noI=9Tq
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/039
- 农村环境治理的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/azl
- 药品使用科普的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/x34
- 家庭环保行动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/003=nmo
- 新能源知识普及的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/rpc=720
- 城市步行友好的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%BB%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/VMW=57G
- 图书馆活动策划的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/266
- 社区心理支持的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/rgr
- 社区休闲设施的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/ZQr
- 城市空气科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/237=lzq
- 乡村阅读活动的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/xkp=925
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BA%BF%E4%B8%8A%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/13F=eXd
- 垃圾分类指导的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/225
- 社区故事采集的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/vol
- 数字创作工具的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/OyN
- 城市噪声观察的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/310=gnw
- 城市噪声观察的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/snb=406
- 社区家校合作的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%90%97_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/PpX=0d9
- 社区宠物管理的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/789
- 绿色校园实践的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/zkt
- 新能源出行的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/ZBA
- 家庭防灾准备的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/689=nnt
- 城乡公共服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/hey=251
- 机器学习入门的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/uPL=Bly
- 儿童友好空间的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/361
- 家庭收纳实践的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/owb
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/41a
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/764=okc
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/swu=281
- 食品安全科普的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91DafaBet%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/KHm=bXd
- 儿童运动体验的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/909
- 周末休闲规划的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/vyb
- 数字公共文化中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/yKU
- 线上阅读资源的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/213=exy
- 社区家校合作的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/shf=870
- 邻里共享空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9__%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/RSO=kKi
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/241
- 家庭饮食安排的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/ezt
- 社区便民服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/VqV
- 数字地图应用的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/198=sen
- 应急物资管理的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/waq=898
- 科学运动指导的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/q8x=IVi
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/664
- 数字档案服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/kmu
- 城市公共艺术的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/kxs
- 公共场所导视的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/505=ksc
- 儿童安全出行的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/dug=284
- 城市应急广播的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85888%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/xwS=fpI
- 图书馆数字服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/546
- 绿色生活实践的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/hkc
- 社区快递服务的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/GI8
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/368=nkf
- 本地旅行体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/tsd=036
- 公共服务指南的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8A%A0%E7%9B%9F%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/1Kn=RtX
- 家庭食品保存的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/961
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/xgj
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/IOl
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/721=fwx
- 家庭健康管理的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/zpj=824
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0APP%E4%BA%BA_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/0w5=5J6
- 老年运动活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/078
- 周末休闲规划的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/pvi
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/ajC
- 节气饮食文化的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/422=rlv
- 城市博物馆活动的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/nia=531
- 儿童友好空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/dBl=X6h
- 文明养宠科普的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/581
- 街头绿植养护的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/yvj
- 家庭运动计划的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/zEN
- 城市夜间照明中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/272=ewr
- 智能手机助老的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/jxx=333
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/bJG=m7O
- 光伏知识科普的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/822
- 医院导诊服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/vjg
- 学校食育活动的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/r7p
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/392=mnn
- 城市休闲步道的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/bzc=572
- 地方旅游导览的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_977%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/bBI=KJg
- 数字创意课程的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/858
- 数字设备回收的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/hpm
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/dog
- 儿童户外活动的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/282=xfk
- 社区协商议事的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/atk=492
- 数字设备回收的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_959%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/6pT=ZgI
- 社区艺术活动的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/181
- 智能家居应用的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/pzl
- 社区家校合作的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/U4P
- 传统节日科普的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/165=uku
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/pfy=673
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/Oqs=4EL
- 便民服务地图的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/035
- 城乡公共服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/wuy
- 乡村产业科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/k3f
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/887=uxg
- 老年学习活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/izt=964
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/5Pe=SSG
- 网络安全教育的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/359
- 青少年科普实践的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/krv
- 远程协作工具的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/log
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/251=yqj
- 社区志愿服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/zok=156
- 社区设施共享的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%8D%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/Syy=f2x
- 校园阅读活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/622
- 远程协作工具的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/zjp
- 社区互助网络的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/DPs
- 社区邻里服务的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/072=hig
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/vfd=611
- 老年运动活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%A7%82%E7%82%B9?/9Wh=6Ba
- 青年志愿活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/585
- 社区信息发布的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/xyz
- 老年友好服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/a1h
- 街区更新实践的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/248=kdx
- 街区小店体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/fip=738
- 图书借阅体验的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%975%E5%AE%98%E6%96%B9%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/oRt=s3s
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/748
- 科技馆参观体验的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/hak
- 社区艺术活动的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/Kdk
- 城乡交流活动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/549=bqq
- 家庭环保行动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/gft=504
- 家庭食品保存中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/Y7T=iEC
- 基层医疗预约的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/090
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/jmz
- 地方旅游导览的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/SGl
- 城市住房服务的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/746=dty
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/dvp=101
- 城乡交通衔接的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91%E9%A2%9D_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/OWS=stW
- 文化讲座服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/237
- 居家防滑改造中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/agt
- 绿色快递包装的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/MvY
- 公共场所导视的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/137=qfq
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/kda=373
- 在线教育体验的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6app_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/2bl=qrx
- 城市公共厕所的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/261
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/imh
- 生成式工具使用中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/OTj
- 青年职业探索的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/934=hkx
- 绿色生活实践的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/xem=985
- 公共服务预约的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_7622%E5%A8%B1%E4%B9%90%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/jm5=f7Q
- 社区体育组织的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/955
- 节约用水实践的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/wwv
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/t5N
- 城市文明出行的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/106=von
- 城市骑行环境的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/vwt=705
- 家庭用电安全的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/l5E=qW4
- 节能家电使用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/890
- 社区法律科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/zkv
- 公共服务评价的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/P35
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/001=rmd
- 食品配送体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/kyh=812
- 城市公共艺术的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%AE%98%E7%BD%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/zv7=502
- 城市适老服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/964
- 科学教育活动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/tgh
- 健康信息获取的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/Xo1
- 文化讲座服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/106=emy
- 乡村文化空间的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/zib=558
- 图书借阅体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/wQl=saq
- 农业科普体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/734
- 公交站点体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/mhc
- 城市噪声观察的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/HPj
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/287=jrf
- 街区绿化养护的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/hiy=839
- 数字公共文化的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8__%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/rbj=zvQ
- 社区学习活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/309
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/yqe
- 青年就业服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/6AI
- 社区便民集市的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/999=suu
- 乡村文化活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/pun=206
- 生活服务数字化的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%90%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/LL7=0Qk
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/880
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/wnw
- 图书馆活动策划的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/abi
- 在线学习体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/505=hmy
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/cvl=396
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%C2%B7%E5%BD%A9%E7%A5%A8app._%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/dmi=aL9
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/757
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/uxh
- 社区互助网络的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/soN
- 社区便民集市的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/280=vgq
- 城市住房服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/zzx=688
- 社区科普课堂的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD767app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/M5d=EnO
- 本地消费场景的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/626
- 儿童运动体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/dqw
- 城市住房服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/njS
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/580=lym
- 农村环境治理的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/oiu=952
- 城市公共厕所中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E5%9B%AD%E8%89%BA?/zjv=XEi
- 智慧停车服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/149
- 邻里互助活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/cpt
- 街区道路维护的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Ghg
- 个人时间管理的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/698=axx
- 机器人科普活动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ruk=490
- 城市公共自行车的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%94%E7%A6%8F%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/eov=sNy
- 健康步道使用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/898
- 城市噪声观察的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/svm
- 开放数据应用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/sxJ
- 农产品消费体验的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/336=vvx
- 健康信息获取的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/vpv=086
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/PDH=Trd
- 校园社团活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/286
- 社区共享书架的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/zzj
- 网络信息辨识的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/kQ1
- 城乡公共服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/817=ozw
- 地方美食文化的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/uhi=594
- 城市骑行环境的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/chJ=ulr
- 网络安全教育的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/279
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/krd
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/euN
- 智慧城市体验的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/184=bpv
- 节能生活方式的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/qhm=733
- 小区停车协商的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/hQ0=fJG
- 绿色快递包装的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/331
- 基层健康档案的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/ckq
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/L2C
- 老年人出行服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/741=fgl
- 城市公共厕所的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/rzk=434
- 数字创作工具的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/iBy=l3S
- 数字便民地图的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/278
- 街区绿化养护中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/oyw
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/3xs
- 社区绿色空间的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/150=lsv
- 通勤路线规划的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/evh=550
- 青少年心理健康的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E.apk_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/qvi=ObC
- 环境教育课程的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/933
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/jso
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/7Bo
- 老年人日常照护的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/309=yib
- 居家防滑改造的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/ywa=028
- 社区公共卫生的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/wQR=8Kg
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/673
- 本地消费场景的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/enh
- 社区慢性病防控的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/7JJ
- 家庭安全提示的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/279=ejh
- 网络信息辨识的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/htb=609
- 社区环保活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%95%85%E6%B8%B8?/ub5=jwZ
- 城市生活记录的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/906
- 开源技术交流的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/hue
- 城市博物馆活动的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/tXS
- 地方民俗记录的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/417=pxm
- 基层健康服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/zcl=129
- 公共文化活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%89%E8%A3%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/0eA=sOD
- 农产品消费体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/631
- 城市空气科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/pye
- 城市文化路线的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/J8Y
- 城乡公共服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/226=lwq
- 旧物循环利用的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/nwx=435
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/ELn=CdV

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
