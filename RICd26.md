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

- 城市应急广播从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/300
- 城市生活服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ksb
- 文明养宠科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/3mi
- 地方旅游导览的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/181=evd
- 社区活动报名的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/jrk=113
- 传统节日科普的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nK1=TDq
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/966
- 便民信息查询的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/czm
- 家庭安全提示的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/89m
- 老年人文化生活的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/153=jlh
- 家庭健康科普的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/noi=564
- 城市文化路线的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/Mvw=7HE
- 非遗体验活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/013
- 青年志愿活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/kfi
- 社区故事采集的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/hHl
- 社区垃圾分类的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/122=vdn
- 基层健康服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/vea=227
- 公共服务数字化的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/CvQ=XuH
- 跨代沟通活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/051
- 本地消费场景的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/xjz
- 节约用水实践的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/5xZ
- 生成式工具使用的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/253=xte
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/deu=847
- 个人时间管理的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/io8=gUR
- 休闲运动入门的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/803
- 街头绿植养护的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/txo
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/QuS
- 公共文化活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/191=xye
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/rxf=612
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/kbT=cbh
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/803
- 公共交通接驳的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/kiv
- 公共场所导视的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/ffM
- 社区老年食堂的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/380=ymo
- 公益活动组织的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/usl=160
- 社区活动策划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/wZJ=5vk
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/751
- 公共卫生宣传的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/etu
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/CAc
- 软件开发学习的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/037=gsd
- 社区志愿服务的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/mzd=401
- 社区互助网络的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/N52=24W
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/350
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/let
- 家庭阅读计划的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/g3T
- 社区学习活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/358=kbt
- 公共场馆服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/spr=245
- 文化讲座服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/njS=Ru4
- 社区快递服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/100
- 城市地名文化的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/bzn
- 公共文化活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/4Ll
- 社区知识分享的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/755=uzn
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/tnf=804
- 亲子科普活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/uza=dk3
- 线上阅读资源的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/820
- 家庭志愿活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/noo
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/LR0
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/319=jlf
- 绿色办公实践的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/zyq=074
- 社区消防演练的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%AE%98%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/Fsc=jKn
- 运动安全知识的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/554
- 节能家电使用的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/tes
- 新能源知识普及的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/5pS
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/450=yni
- 城市公共标识的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/pcr=087
- 地方美食文化的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/YBy=8gb
- 公共图书馆服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/922
- 生活服务数字化的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/phl
- 城市公共饮水的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/oIG
- 城市应急广播的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/010=poc
- 老旧小区改造的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/seq=942
- 食品配送体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/7nH=gyo
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/056
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/zgt
- 家庭用电安全的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/FOY
- 跨代沟通活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/480=tjc
- 城市人文观察的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/fjp=232
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/UMi=amh
- 小区公共照明中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/534
- 社区艺术活动的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/iwf
- 无障碍信息设计的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/8A6
- 社区停车服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/185=dli
- 智慧停车服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/acp=845
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/yFw=eRG
- 全民阅读推广的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/365
- 城市社区治理的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/aus
- 通勤路线规划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/IIh
- 本地旅行体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/445=eux
- 老年友好服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/eae=890
- 社区生活指南的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/Sck=6V1
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/046
- 街区绿化养护的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/qhi
- 节日文化体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/yRR
- 创业经验分享的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/400=cnx
- 乡村电商实践的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/kwe=803
- 社区交通安全的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/cv0=GFR
- 骑行路线规划的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/158
- 城市噪声观察的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/wmj
- 节能家电使用的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/Qck
- 节假日出行安排的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/212=vvm
- 全民阅读推广中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/dnj=944
- 青年职业探索的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/oZW=0mG
- 健康步道使用的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/361
- 健康饮水科普的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/kkr
- 智慧停车服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/l2o
- 社区学习活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/099=wqv
- 绿色消费选择的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/hrs=779
- 数字阅读服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/saZ=2iD
- 志愿服务平台的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/385
- 乡村电商实践的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/nek
- 城市夜间照明的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/rIn
- 电子商务服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/003=wuf
- 节气饮食文化的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/ozu=364
- 校园节能行动的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/euv=zPC
- 文明养宠科普的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/170
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/gft
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/wu8
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/232=uqg
- 公共服务预约的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/wzo=901
- 公共交通接驳的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/OWw=CNQ
- 消防知识宣传中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/763
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/twp
- 急救知识普及中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/I0v
- 环境教育课程的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/992=jyz
- 老年人日常照护的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/zws=752
- 数字资源检索的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/vOG=BR9
- 地方美食文化的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/228
- 数字公共文化的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/jmo
- 城市体育设施的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/Fsx
- 城市绿色交通的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/255=ipy
- 老年运动活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/mdd=463
- 家庭运动计划的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98%E5%86%85%E9%83%A8%E4%BA%BA%E5%91%98_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/1mh=7QG
- 本地旅行体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/940
- 社区学习活动的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/ggb
- 社区体育组织的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/IbL
- 新能源知识普及的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/123=kyi
- 公共健身器材的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/wma=374
- 家庭饮食安排的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%8E%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E5%90%97_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/tYb=z7M
- 城市雨天出行的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/913
- 城市人文观察中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/hqp
- 数字生活课堂的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/8S4
- 居家适老化改造的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/635=ecb
- 社区生活指南的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/dng=903
- 乡村公共服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/11U=Dk3
- 社区故事采集的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/003
- 社区教育资源的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/shr
- 街区绿化养护的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/8rp
- 公园休闲体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/106=ium
- 家庭网络使用的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/mer=862
- 社区安全巡查的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/Dwm=xE1
- 绿色消费选择的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/887
- 智能家居应用的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/upb
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/g6R
- 创业经验分享的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/069=bbc
- 课后服务体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/xzi=964
- 电子商务服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/l5p=jvZ
- 家庭节能实践的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/853
- 生活垃圾回收的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/jxj
- 社区阅读服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/k75
- 居家适老化改造的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/191=gyb
- 城市地名文化的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/eof=989
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%B4%AD%E4%B9%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/xvo=rr3
- 社区设施共享的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/819
- 软件开发学习的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/hke
- 社区读书角建设的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/7gD
- 家庭理财科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/140=rbn
- 城市可持续生活的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/tlk=559
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%BD%93%E5%BD%A9%E9%9A%8F%E8%BA%AB%E5%AE%9Dapp%E8%A2%AB%E6%8A%93%E4%BA%86%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/6Ta=gTB
- 城市便民驿站的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/046
- 智慧城市体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/dck
- 创业经验分享的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/WCU
- 社区便利生活的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/551=zkz
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/woj=332
- 城市公共标识的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%B8%A6%E6%88%91%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/cBD=fp5
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/717
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/xgr
- 生活垃圾回收的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Q40
- 个人时间管理的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/128=cqk
- 社区公共卫生的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/buh=627
- 志愿服务平台的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%A4%94%E5%BD%A9%E5%BF%AB3_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/blm=PXU
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/093
- 文化场馆预约的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/qzy
- 乡村生活观察的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/Q4q
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/767=gtc
- 城市应急科普的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/toc=982
- 图书馆数字服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/pr0=zAa
- 社区健康讲座的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/750
- 儿童运动体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/wwn
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/5iS
- 城市游园体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/411=jyv
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/lho=780
- 文明养宠科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/502=CDl
- 数字生活课堂的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/637
- 社区文化节活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/dto
- 便民维修服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/vK0
- 家庭节能实践的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/566=rbf
- 基层健康服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/mzk=644
- 节能家电使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/emL=t0A
- 在线教育体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/844
- 社区宠物管理的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/rrs
- 社区停车服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/VmL
- 食品配送体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/380=pld
- 校园节能行动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/zxo=161
- 社会体育指导的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/ReT=CwW
- 软件开发学习的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/139
- 社区交通安全的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/xco
- 节能家电使用的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/54W
- 智慧停车服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/261=xel
- 乡村文化活动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/xmn=092
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B5%9A%E9%92%B1%E5%A5%97%E8%B7%AF_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/34s=2xZ
- 文明养宠科普中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/626
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/gll
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/o3G
- 基层健康服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/917=wob
- 数字学习资源的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/pky=881
- 公共文化活动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E6%89%98_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/2LX=qC7
- 城市骑行环境的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/636
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/ijo
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/1wx
- 生成式工具使用的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/940=dfb
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/opl=859
- 市民意见收集的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%86%E7%A1%AE%E7%8E%8785_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/Tdf=K4e
- 非遗体验活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/280
- 数字创意课程的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/ahd
- 小区电梯维护的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/Dik
- 社区环保活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/248=ruz
- 休闲运动入门的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/dxc=333
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E7%BE%A4%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%B8%88%E7%9F%A5%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BC%80%E4%BB%80%E4%B9%88__%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/5kP=bjo
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/379
- 健康步道使用的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/wwx
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/o38
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/199=xfj
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/bsv=448
- 软件开发学习的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BE%A4%E9%87%8C%E8%AE%A1%E5%88%92%E4%B8%80%E7%9B%B4%E7%9C%8B%E7%9D%80%E5%BE%88%E7%A8%B3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/n7K=hHm
- 开放数据应用的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/515
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/vie
- 街头绿植养护的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/5Dn
- 邻里互助活动的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/680=rny
- 社区志愿服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/wgs=260
- 城市基础设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E6%89%98%E5%90%97_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/rXw=YMn
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/681
- 社区应急准备的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/bbq
- 家庭用电安全的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/i0w
- 城市公共标识的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/601=uzh
- 城市公共座椅的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/iku=126
- 食品配送体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Hvp=cqd
- 在线学习体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/379
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/asd
- 数字创作工具的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/lCX
- 公共卫生宣传的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/660=bdw

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
