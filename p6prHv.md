# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 社区活动报名的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8C%97%E4%BA%ACPK10%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/TTr
- 数字生活课堂的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8C%97%E4%BA%ACPK10%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/899=pgc
- 校园社团活动的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8C%97%E4%BA%ACPK10%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/vaj=688
- 家庭健康科普的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8C%97%E4%BA%ACPK10%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/eRE=tNF
- 城市夜间照明的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/713
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/jgr
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/erN
- 社区文化节活动的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/249=oyw
- 青少年科技社团的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/iyj=450
- 在线教育体验的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/yeN=lpK
- 学校体育活动的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/370
- 城市建设科普的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/gjy
- 数字资源检索的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/TNK
- 家庭园艺实践的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/749=vrp
- 绿色生活实践的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/sse=123
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/4Bv=7CS
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/294
- 社区家校合作的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/inc
- 儿童安全出行的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/jzo
- 课后服务体验的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/030=bcu
- 老年运动活动的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/mft=524
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%927%E7%A0%81_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/IQD=2RO
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/362
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/uyn
- 节假日出行安排的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/SWK
- 科学健身方法的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/988=baw
- 人工智能科普的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/hth=025
- 乡村公共服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/AFJ=wTD
- 社区应急准备的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/881
- 新能源知识普及的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/lij
- 小区停车协商的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/o9X
- 个人时间管理的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/405=gsw
- 乡村生活观察的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/xld=384
- 社区便民服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/KOj=XuG
- 街道综合服务的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/629
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/xyt
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/Ykr
- 数字创意课程的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/305=vtv
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/dqi=910
- 家庭运动计划的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922023_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/aRY=G41
- 城市公共标识的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/372
- 农村环境治理的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/wnt
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/U4g
- 市民意见收集的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/387=gol
- 全民健身活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/ton=329
- 公共卫生设施的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/Q70=WuK
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/361
- 城市文明出行的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/omm
- 城市公共厕所的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/wt8
- 城市公共空间的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/817=yrs
- 家庭阅读计划的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/hbb=446
- 城市慢行系统的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%8C%97%E4%BA%AC%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/OS4=pxT
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/352
- 智能家居应用的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/wqe
- 社区读书角建设的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/srE
- 数字课堂应用的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/976=bsq
- 新能源出行中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/kji=308
- 地方美食文化的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/cDv=NuA
- 数字支付体验的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/238
- 环境教育课程的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/jpd
- 数字创意课程的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/S4D
- 个人数据管理的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/191=ihl
- 地方文化传播的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/kog=733
- 城市适老服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/msj=9nj
- 家庭急救准备的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/632
- 城乡交流活动的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/ugv
- 个人时间管理的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/FOM
- 乡村生态观察的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/076=uxr
- 社区科普课堂的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/wcp=865
- 图书馆活动策划的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%87%E8%83%BD5%E7%A0%81%E5%BE%AA%E7%8E%AF%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/usk=lJk
- 学校体育活动的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/566
- 家庭节能实践的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/onx
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/PL9
- 公共交通接驳的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/617=nwy
- 街区小店体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/hhd=600
- 家庭用电安全的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%85%E7%BD%AEMOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/ZYo=1N5
- 社区家校合作的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/947
- 科普展览体验的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/pmm
- 基层健康服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/IIz
- 数字生活课堂的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/791=xzx
- 城市公共标识的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/mmp=406
- 社区修缮行动的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E9%87%91%E5%B8%81_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/Ho2=IuQ
- 城市展览体验的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/875
- 安全出行教育的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/tcn
- 社区便民服务的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/dNj
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/656=zea
- 电子商务服务的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/uel=333
- 街道综合服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BC%A4%E7%BA%B7%E8%B4%BA%E8%AF%AD%E9%9B%86%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/3w7=sGa
- 老年运动活动的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/638
- 便民服务地图的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/cvr
- 社区活动空间的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/CpJ
- 绿色生活实践中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/320=hmo
- 科学教育活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/tym=730
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%AE%A1%E7%90%86%E5%91%98%E6%A8%A1%E5%BC%8F_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/VZq=dEV
- 应急物资管理的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/329
- 青年志愿活动的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/pxv
- 数字政务体验的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/yXM
- 公园休闲体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/416=hsk
- 乡村文化活动的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/gbx=171
- 应急物资管理的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E6%B8%B8%E6%88%8F_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/SWP=ZmF
- 乡村文化活动的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/643
- 城市文明出行的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/rco
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/mNY
- 老年运动活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/151=vtp
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/yde=352
- 城市应急广播的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/5Z3=Epy
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/012
- 街区绿化养护的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/lca
- 城市公共座椅的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/SGA
- 公共空间照明的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/823=lmg
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/mgk=659
- 城市绿色交通的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/Bov=4EJ
- 街区更新实践的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/198
- 节能家电使用的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/nxv
- 社区垃圾回收的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/Xei
- 节约用水实践的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/541=okd
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/wrf=310
- 基层医疗预约中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_168%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/dtG=ufK
- 垃圾分类指导的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/865
- 学校食育活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/cuq
- 家庭网络使用的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/cqS
- 应急物资管理的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/411=omw
- 节能家电使用的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/uwt=820
- 公共设施维护的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_1%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E5%AE%B6%E5%B1%85?/7Zg=BR2
- 公共服务评价的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/398
- 城市步行环境的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/vpx
- 校园阅读活动的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/LVK
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/995=sav
- 数字阅读服务的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/wsx=950
- 医院导诊服务的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/5y8=qjY
- 应急物资管理的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/803
- 家庭理财科普的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/wve
- 非遗课堂体验的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/qgH
- 通勤路线规划的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/010=eri
- 数字学习资源的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/dmw=786
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%87%91%E5%B8%81%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/7eD=auL
- 儿童运动体验的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/801
- 家庭健康管理中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/yce
- 公共场馆服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/Po4
- 电子商务服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/564=wii
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/xhn=426
- 乡村生态观察的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/NcX=qMl
- 老年人出行服务的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/870
- 青年职业探索的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/veo
- 青少年编程学习的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/PcR
- 数字艺术创作的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/733=mfb
- 本地旅行体验的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/qar=450
- 个人信息保护的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/1uz=u8c
- 社区宣传栏更新的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/758
- 社区体育组织中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/jyi
- 城市展览体验的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/0Q4
- 智慧停车服务的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/268=kqi
- 城市公共空间的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/tbf=024
- 城市博物馆服务的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_138%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/EVb=kRY
- 公共卫生设施的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/089
- 城市噪声观察的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/xmw
- 数字支付体验的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/B7Z
- 便民服务地图的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/872=wzx
- 社区宠物管理的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/bmx=907
- 通勤路线规划的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/QuN=DqK
- 社区公共卫生的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/286
- 社区快递服务的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/vbp
- 租房信息服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/baP
- 社区宠物管理的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/262=hos
- 数字公共文化的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/air=194
- 乡村生态观察的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%9A%E5%B0%91%E9%92%B1_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/2ZG=3xd
- 节能生活方式的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/573
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/axx
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/KtT
- 个人信息保护的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/819=xbn
- 社区科普课堂的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/uti=982
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_168%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/1GB=a2T
- 城市博物馆服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/574
- 家庭安全提示的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/mxl
- 城市骑行环境的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/uzg
- 基层医疗预约的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/036=dlu
- 社区便民集市的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/olr=665
- 垃圾分类指导的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/bKO=Izc
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/578
- 城市公共座椅的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/gmg
- 社区生活指南的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/Z2n
- 社区垃圾回收的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/031=yhx
- 社区故事采集的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/qzn=251
- 公共服务沟通的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_2024%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/ZFb=rIv
- 公共卫生设施的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/663
- 老年智能设备的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/ktq
- 智慧城市体验的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/62K
- 城市运动公园的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/864=vci
- 小区公共照明的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/ahl=469
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/PNH=fpg
- 居家防滑改造的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/551
- 志愿服务平台的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/rsp
- 图书馆活动策划的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/1D3
- 健康步道使用的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/184=ipt
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/htb=334
- 电动汽车充电的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/svu=G4K
- 旧物循环利用的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/531
- 节气饮食文化的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/pbq
- 城市适老服务的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/w0m
- 城市体育设施的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/559=prq
- 创业经验分享的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/esz=645
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E4%B8%AA%E6%9C%80%E4%BD%B3%E5%8E%8B%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/Dxm=vKY
- 电动汽车充电的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/845
- 城市地名文化的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ldh
- 口袋公园建设的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/D25
- 休闲运动入门的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/066=uxh
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/mnv=657
- 本地消费场景的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%81%E7%A8%B3%E8%B5%9A%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/3C9=F8K
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/791
- 家庭节能设备的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/csu
- 数字公共文化的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/HuX
- 社区信息发布的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/457=wio
- 数字公共文化的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/ljt=918
- 城市运动公园的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%956%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/2Ms=JnH
- 公共空间休憩的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/109
- 新能源知识普及的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/lnn
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/5wi
- 健康饮食教育的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/223=kzn
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/sju=548
- 生活垃圾减量的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%94%A8%E4%B8%87%E8%83%BD%E5%9B%9B%E7%A0%81%E8%83%BD%E7%AE%97%E5%87%BA%E4%B8%8B%E6%9C%9F%E5%A5%96%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/ivf=H6C
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/518
- 环境教育课程的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sim
- 城市便民驿站的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/4ig
- 居家适老化改造的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/495=dqg
- 乡村教育资源的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pkc=504
- 社区邻里服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_2%E7%BB%845%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ybn=Ect
- 儿童安全出行的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/443
- 城市公共空间的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/qtp
- 农产品消费体验的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/hQx
- 校园社团活动的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/061=bix
- 家庭收纳实践的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/iqh=183
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61470%E5%8F%B7%E7%A0%81%E6%8A%80%E5%B7%A7_360%E6%B3%95%E6%B2%BB?/LSm=PDg
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/022
- 社区协商议事的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/zdo
- 社区托育服务的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/tkt
- 信息无障碍体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/983=mya
- 老年学习活动的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/shb=820
- 城乡公共服务中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/wFz=x0K
- 社区邻里服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/433
- 社区交通安全的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/ysf
- 个人时间管理中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/1sw
- 数字艺术创作的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/074=mob
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/yqi=672
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C021%E9%81%97%E6%BC%8F%E6%89%93%E6%B3%95_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/lC4=LWx
- 公共空间照明的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/385
- 社区文化传播的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/iox
- 社区体育组织的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/Vz8
- 线上办事服务的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/081=bxv
- 数字学习资源的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/ner=104
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C%E5%9B%BE_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/yoC=LtH

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
