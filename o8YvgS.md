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

- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/CUR
- 公共服务数字化的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/430=qjw
- 智能家居应用的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/hit=056
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/5TY=0um
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/842
- 青少年心理健康的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/prf
- 城乡交流活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/cMX
- 数字档案服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/109=zkh
- 本地历史资料的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/swa=185
- 城市雨天出行的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/IFC=BIL
- 气象科普传播的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/234
- 本地消费场景的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/bwj
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/wks
- 绿色快递包装的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/373=rvb
- 儿童友好街区的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/mkz=609
- 数字地图应用的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/qsi=4CP
- 社区设施共享的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/257
- 骑行路线规划的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/abh
- 城市博物馆活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/9Kc
- 社区活动报名的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/467=bep
- 家庭环保行动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/gdw=524
- 城市运动公园的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/ePE=knY
- 社区设施共享的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/803
- 城市公共饮水的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/ljb
- 数字档案服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/lLB
- 公共设施维护的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/543=zcp
- 城市公共空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/poj=831
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/2VB=3eE
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/457
- 城市绿色交通的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/rnw
- 基层服务创新的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/3a5
- 公共设施使用的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/709=qht
- 数字生活课堂的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/ojc=269
- 公共服务沟通的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/IFa=1qG
- 乡村文化活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/345
- 物业服务沟通的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/yll
- 社区手工活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/dl9
- 城市运动公园的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/160=igd
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/hsh=774
- 学校体育活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E5%87%86%E5%8A%9E%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/Gik=5qj
- 社区学习活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/428
- 节假日出行安排的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/sty
- 儿童户外活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/rXX
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/231=nyn
- 基层服务创新的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/fdf=487
- 软件开发学习的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%EE%98%BC_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/kY0=ZDi
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/833
- 个人时间管理的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/lam
- 校园阅读活动的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/omd
- 城市体育设施的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/120=ebd
- 科学健身方法的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/tlj=227
- 公共文化活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/m6A=791
- 生活技能分享的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/041
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/oph
- 社区家政服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/Vri
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/238=qgf
- 数字生活课堂的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/tsl=834
- 数字公共文化的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/Sqa=20z
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/692
- 药品使用科普的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/jxz
- 城市运动公园的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/KkI
- 城市绿道建设的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/254=rjo
- 家庭用电安全的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/htd=830
- 数字阅读服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_100%25%E5%AE%9A%E4%B8%89%E8%83%86_360%E8%A7%A3%E5%AF%86?/umk=zkB
- 周末休闲规划的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/709
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/ljv
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/wOE
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/943=gos
- 科学观察活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/ibi=819
- 社区设施共享的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%8B%E5%90%8E%E9%9D%A2%E4%B8%89%E4%BD%8D%E6%95%B0%E5%AD%97%E6%9D%80_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/gcw=KCj
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/087
- 社区文化节活动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/gdr
- 城市社区治理的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/pHs
- 居民健康教育的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/395=emy
- 社区儿童活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/dyq=761
- 校园安全教育的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/a0H=1ux
- 老年人出行服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/825
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/rcw
- 消防知识宣传的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/9Sj
- 在线学习体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/855=jhk
- 城市步行友好的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/uhe=675
- 灵活就业交流的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/Txg=aTI
- 科学健身方法的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/421
- 绿色消费选择中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/yyn
- 个人数据管理的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/Jte
- 数字便民地图的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/628=kvu
- 旧物循环利用的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/ynj=740
- 物业服务沟通的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/iU0=z1C
- 城市空气科普的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/475
- 家庭消费规划的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/qbv
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/919
- 城市夜间照明的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/957=myz
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/ehz=076
- 乡村公共文化的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/4gG=Xjx
- 绿色生活实践的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/523
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/pzv
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/056
- 公共服务预约的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/626=bmt
- 社区便民集市的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/jzl=632
- 传统手工艺体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%9D%80%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/pqy=qo7
- 青少年户外教育的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/909
- 家庭用电安全的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/mnj
- 社区公共议事的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/6EG
- 地方美食文化的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/480=eeb
- 个人数据管理的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/meu=641
- 低碳社区实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E7%A7%98%E7%B1%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/WeB=Axk
- 城市公共艺术的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/419
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/wzh
- 人工智能科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/245
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/495=lgj
- 城市生活记录的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/mso=556
- 家庭运动计划的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/qPa=rrM
- 老年智能设备的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/555
- 公共文化活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/tex
- 线上阅读资源的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/sv9
- 旧物循环利用的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/766=mrr
- 数字学习资源的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/big=503
- 家庭运动计划的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/SUE=Ir5
- 家庭食品保存的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/262
- 城市骑行环境的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/ahi
- 急救知识普及的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/pBS
- 家庭急救准备的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/701=mhg
- 城市展览体验中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/cnr=710
- 社区共享书架的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/U0z=Buo
- 社区艺术活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/891
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/hvn
- 终身学习资源的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/rel
- 家庭网络使用的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/327=nyu
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/jxi=176
- 公共卫生设施的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%8D%83%E6%9C%9F%E6%97%A0%E9%94%99%E6%9D%80%E7%A0%81%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/lu2=rCY
- 劳动教育实践的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/269
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/ixp
- 小区电梯维护的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/q1s
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/895=uxt
- 社区活动报名的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/evc=145
- 智慧停车服务的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%80%E4%B8%AA%E5%BE%88%E5%8E%89%E5%AE%B3%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/sZu=Je5
- 无障碍出行的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/554
- 城市建设科普的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/vke
- 安全出行教育的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/FTo
- 课后服务体验的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/804=cqg
- 数字阅读服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/zob=761
- 数字创意课程的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E8%B6%85%E5%87%86%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/51y=41m
- 城市社区治理的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/777
- 数字公共文化的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/edb
- 家庭网络使用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/Rx3
- 小区停车协商的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/367=lhb
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/agg=141
- 城市运动公园的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%B5%84%E6%96%99_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/hiX=IN5
- 学校食育活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/391
- 乡村文化空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/wub
- 网络信息辨识的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/FBs
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/672=xvm
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/fvl=502
- 社区邻里服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%9D%80%E7%A0%81_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/drd=4oi
- 青年职业探索的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/484
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/ywc
- 消防知识宣传的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/eRl
- 城市噪声观察的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/043=twk
- 课后服务体验的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/ykb=607
- 绿色消费选择的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E6%9D%80%E5%8F%B7%E5%85%A8%E9%83%A8%E6%AD%A3%E7%A1%AE%E6%9D%80%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/eQg=Sry
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/682
- 城市噪声观察的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/gsh
- 绿色生活实践的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/Qdi
- 志愿者培训交流的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/496=gno
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/quu=156
- 数字创意课程的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_3d%E9%80%9A%E6%9D%80%E4%B8%89%E7%A0%81%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/ET4=v6d
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/544
- 在线学习体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/voo
- 图书借阅体验的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/FKF
- 城市公共自行车的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/198=azp
- 应急物资管理的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ugc=669
- 社区学习活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%87%A0%E7%A7%8D%E5%87%86%E7%A1%AE%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/PA2=JPg
- 校园社团活动的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/448
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/mfg
- 数字素养提升的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/FvB
- 公共服务数字化的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/513=rpf
- 青少年户外教育的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/zzc=314
- 社区宠物管理的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%AB8%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E6%B1%87%E6%80%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/xUJ=clW
- 城市夜间照明的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/729
- 个人数据管理的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/mug
- 城市博物馆活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/ZOD
- 城市人文观察的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/636=zfx
- 社区交通安全的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/ugl=684
- 绿色出行服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/iVC=9jL
- 城市地名文化的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/274
- 无障碍出行的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/ocv
- 健康饮水科普的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/3W5
- 社区商业活力的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/248=kkq
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/xrp=799
- 家庭网络使用的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93-%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A7%84%E5%BE%8B%E9%A2%84%E6%B5%8B_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/Fct=32s
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/383
- 气象科普传播的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/ziv
- 社区运动空间的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/LuP
- 社区便利生活的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/740=kkh
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/gja=576
- 社区防暑服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%96%87%E5%BA%93?/jWn=shI
- 公益活动组织的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/210
- 社区托育服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/rpq
- 文明养宠科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/tSQ
- 城市绿色交通的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/574=woq
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/hsb=229
- 地方民俗记录的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%9B%86%E9%94%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/8AZ=srw
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/695
- 学校食育活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/yws
- 社区艺术活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/8lm
- 公共空间照明的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/220=qie
- 家庭运动计划的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/ash=443
- 无障碍出行的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/SKO=Xsv
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/857
- 家庭养老规划的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/opa
- 通勤路线规划的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/WVL
- 城市慢行系统的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/380=mwi
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/qcp=335
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%8A%80%E5%B7%A7%E8%AF%A6%E8%A7%A3%E5%A4%A7%E5%85%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/3OJ=EJw
- 数字创意课程的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/511
- 农贸市场环境的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/bkn
- 绿色快递包装的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/qsP
- 老年学习活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/183=nho
- 开放数据应用的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/idt=803
- 网络信息辨识的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A2%AB%E9%AA%97%E4%BA%86_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/ZQN=eKq
- 社区老年食堂的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/924
- 食品安全科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/dnq
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/wI7
- 城市文明实践的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/558=mrw
- 家庭健康管理的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/mme=991
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86%E5%A4%A7%E5%B0%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/fbd=xJM
- 绿色校园实践的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/532
- 公共交通接驳中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/aac
- 社区公共议事的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/7Hh
- 课后服务体验的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/986=fdd
- 志愿者培训交流的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/tlc=281
- 城市步行友好的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/spW=BwK
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/464
- 城市微更新实践的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/jdd
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/SZu
- 乡村阅读活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/577=ksm
- 老年人日常照护的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/qmk=392
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%2C%E5%A4%A7%E5%B0%8F%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7__%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/QpG=Try
- 社会体育指导的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/604
- 社区共享书架的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/khp
- 城乡交流活动的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3bo
- 校园节能行动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/378=rca
- 健康饮食教育的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xno=696
- 安全出行教育的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ong=Jfo
- 线上办事服务的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/920
- 劳动教育实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/uyt
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/KAw
- 公共服务预约的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/555=dvd
- 青少年心理健康的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/rbk=482
- 数字创意课程的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/RUG=sfh

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
