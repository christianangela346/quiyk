# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 乡村教育资源的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E5%8D%95-%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/kgu=542
- 公益活动组织的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E5%8D%95-%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/BAK=FGz
- 社区心理支持的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/337
- 数字设备回收的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/ndq
- 家庭照护支持的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/EJv
- 老年人出行服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/730=cip
- 公共交通接驳的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/hhh=882
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/HRt=Ziw
- 科学健身方法的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/939
- 社区公共餐饮的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/vpo
- 节能家电使用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/iY0
- 健康饮食教育的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/515=ppa
- 城市社区治理的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/icc=625
- 城市夜间照明的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1-%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/Kpb=tvW
- 公园无障碍服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/875
- 城市便民驿站的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/rjd
- 公共场所导视的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/rVP
- 社区花园共建的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/492=hyw
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/zcv=984
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/Q7G=CiV
- 科学运动指导的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/281
- 家庭志愿活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/vdv
- 社区儿童活动的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/cC2
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/016=kny
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/xvr=981
- 公共场所导视的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F-%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/jrc=vg2
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/348
- 农村环境治理的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/jbn
- 文化讲座服务的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/ywL
- 绿色出行服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/821=tbp
- 乡村文化活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/lwt=944
- 绿色校园实践的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/iq5=l2d
- 公共空间休憩的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/628
- 乡村生态观察中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/pie
- 公共服务预约的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/0q3
- 城市空气科普的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/489=ocy
- 节约用水实践的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/zbi=859
- 食品配送体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/63J=H1b
- 公交站点体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/252
- 家庭健康科普的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/wuo
- 开放式学习空间的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/18l
- 社区快递服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/235=myo
- 乡村电商实践的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/got=104
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app-%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/FCY=mTQ
- 社区公共卫生的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/454
- 街区更新实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/geo
- 无障碍信息设计的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/UK4
- 社区商业活力的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/192=zpg
- 公共图书馆服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/ggs=908
- 绿色出行服务的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/wrJ=BuE
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/088
- 公园休闲体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/pml
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/Bi0
- 校园社团活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/356=nkm
- 邻里互助活动的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/ylp=788
- 志愿者培训交流的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9-%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/vZl=Ji1
- 城市共享单车的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/797
- 社区商业活力的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/kbx
- 数字便民地图的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/f3E
- 社区修缮行动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/609=ntu
- 城市共享单车的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/kpk=429
- 数字政务体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/xh7=kjb
- 社区文化传播的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/068
- 社区设施共享的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/pwu
- 社区菜市场服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/f1M
- 公共服务评价中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/470=sih
- 街头绿植养护的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/mui=623
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/o55=rj0
- 智慧停车服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/898
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/vpx
- 远程协作工具的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/jO5
- 儿童友好空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/780=uon
- 社区健康讲座的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/rie=662
- 休闲运动入门的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/dzw=GyU
- 科学运动指导的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/400
- 城市展览体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/lns
- 城市夜间照明的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/0bd
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/638=kww
- 城市生活记录的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/qoc=548
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8-%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/mg6=HcK
- 新能源知识普及的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/585
- 气象科普传播的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/qlz
- 公共服务咨询的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/bmi
- 城市公共厕所的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/720=fwe
- 个人数据管理的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/ukl=582
- 社区应急准备的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/qsY=JGL
- 城市人文观察的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/643
- 本地消费场景的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/amo
- 公共服务评价的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/je6
- 城市应急广播的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/190=zvx
- 社区防暑服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/cge=674
- 信息无障碍体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F-%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/Wmc=CoS
- 城市文化路线的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/195
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/bqh
- 人工智能科普的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/fRT
- 小微企业服务的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/716=zbp
- 旧物循环利用的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/ogn=389
- 农村环境治理的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/WAI=9pm
- 社区知识分享的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/322
- 校园节能行动的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/gec
- 社区教育资源的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/3Nc
- 乡村公共阅读的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/692=svc
- 城市公共艺术的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/spu=691
- 农产品品牌传播的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/cgo=Gz2
- 社区家政服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/328
- 青年职业探索的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/lgl
- 儿童户外活动的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/dTG
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/621=tqu
- 小区停车协商的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/vcx=094
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/Vdz=Bw2
- 城市应急广播的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/849
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/apq
- 社区托育服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/cSY
- 乡村公共服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/302=dnk
- 科学观察活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/fgp=192
- 社区便民集市的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/1Bt=ztj
- 乡村生活观察的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/724
- 邻里共享空间的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/omh
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/gjL
- 家庭急救准备的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/955=grv
- 数字艺术创作的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/cad=878
- 公益活动组织的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/i90=y97
- 社区庭院绿化的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/625
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/ohr
- 公共服务数字化的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/Hhy
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/223=awv
- 终身学习资源的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/klp=042
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88-%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/BRE=foh
- 小区停车协商的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/138
- 社区活动空间的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/rbo
- 城市人文观察的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/i3p
- 家庭健康科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/067=voe
- 乡村生态观察的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/klr=447
- 校园阅读活动的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9-360%E5%85%AC%E5%BC%80%E8%AF%BE?/QX9=g8h
- 全民阅读推广的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/443
- 社区活动空间的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/pqu
- 科技馆参观体验的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/ThK
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/362=ywr
- 家庭用电安全的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/wkj=827
- 城市慢行系统的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/ROo=dYe
- 本地历史资料中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/235
- 城市水环境观察的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/jzi
- 城市夜间照明的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/KvQ
- 家庭理财科普的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/473=ofk
- 开放数据应用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/fpj=109
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91-%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/KD3=ulR
- 社区心理支持的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/272
- 光伏知识科普的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/dpr
- 老年人出行服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/Byb
- 社区消防演练的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/898=jve
- 城市社区治理的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/bzg=498
- 地方旅游导览的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0-%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/SBv=t8Y
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/326
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/jtm
- 城乡公共服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/arn
- 基层健康档案的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/111=aij
- 本地消费场景的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/wzi=422
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86-%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/UKR=Qjr
- 科学教育活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/499
- 社区手工活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/mzy
- 城市社区治理的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/WEt
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/576=abv
- 乡村电商实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/mwt=505
- 公共空间休憩的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/0iI=eT5
- 社区健康讲座的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/347
- 数字创作工具的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/kaf
- 社区家校合作的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/QYc
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/649=hab
- 校园社团活动的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/hbm=060
- 城市地名文化的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/m5a=AUi
- 家庭用电安全的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/432
- 数字设备回收的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/kdw
- 运动安全知识的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/mIs
- 乡村公共服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/875=awv
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/rou=055
- 便民信息查询的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/0Cs=YKj
- 社区家校合作的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/362
- 城市公共饮水的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/pwq
- 社区环保活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/8k7
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/480=gon
- 旧物循环利用的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/uan=541
- 气象科普传播的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88-%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/7Gt=2uB
- 城市建设科普中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/875
- 城市共享单车的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/khl
- 无障碍出行的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/rd4
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/495=fnp
- 城市公共标识的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/vlq=261
- 社区应急准备的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/iPK=Nrs
- 数字生活课堂的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/696
- 社区体育组织的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/sta
- 公共交通接驳的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/YRh
- 城市文化路线的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/709=gar
- 数字课堂应用的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/ynn=997
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/aLr=xPJ
- 老年运动活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/587
- 家庭防灾准备的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/hwi
- 旧物循环利用的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/c0j
- 社区便民服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/891=uzn
- 城市骑行环境的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/jwh=472
- 图书馆活动策划的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91-%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/72i=u6C
- 社区公共卫生的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/455
- 生活技能分享的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/lsk
- 城市运动公园的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/Zfl
- 开源技术交流的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/327=vdq
- 科学教育活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/uso=926
- 消防知识宣传的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/G3y=dSY
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/248
- 老年数字阅读的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/qoi
- 节假日出行安排的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/RCJ
- 环境教育课程的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/332=glb
- 街区更新实践的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/ifx=176
- 社区体育组织的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88-%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/EXq=YKL
- 家庭教育交流的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/379
- 绿色快递包装的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/wlz
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/xop
- 开放数据应用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/177=tbd
- 社区消防演练的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/rve=880
- 家庭网络使用的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88-%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/WCx=jyY
- 街区更新实践的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/642
- 城市骑行环境的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/ubj
- 学校食育活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/Kz4
- 城市文明出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/070=yon
- 生活垃圾减量的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/gla=595
- 基层医疗预约的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6-%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/R2W=XRM
- 城市公共厕所的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/526
- 城市步行友好的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/gvh
- 城市公共座椅的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/6kT
- 医院导诊服务的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/192=gva
- 数字档案服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/srl=999
- 安全出行教育的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/mox=Tdg
- 线上办事服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/655
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/djr
- 家庭节能设备中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/kPm
- 城市绿道建设的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/627=fcy
- 食品安全科普的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/yby=055
- 社区家政服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B-%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/0Xj=C8P
- 青少年心理健康的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/028
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/she
- 生活技能分享的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/CfE
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/521=oio
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/dvt=750
- 生活垃圾减量的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/3K7=LJw
- 家庭消费规划的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/389
- 科学健身方法的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/ivr
- 社区公共卫生的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/vVc
- 社区便利生活的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/126=vqd
- 青年职业探索的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/oki=100
- 小区停车协商的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios-%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/yeO=wGO
- 家庭网络使用的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/510
- 城市骑行环境的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/fzk

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
