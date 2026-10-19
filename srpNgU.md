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

- 低碳社区实践的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/954
- 在线教育体验的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/ili
- 乡村教育资源的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/BmF
- 乡村阅读空间的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/009=jfs
- 城市博物馆服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/ttw=919
- 城市公共厕所的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/H1n=AfR
- 传统节日科普的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/884
- 文化讲座服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/dnx
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/byb
- 便民服务窗口的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/537=jkl
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/eax=667
- 社区艺术活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/Mpc=pp8
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/428
- 急救知识普及的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/kcn
- 社区便利生活的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/tq9
- 开放数据应用的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/455=taf
- 小区停车协商的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/pjy=219
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/V10=wSv
- 低碳社区实践的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/301
- 社区宠物管理的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/jqw
- 城市公共厕所的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/8ws
- 城市住房服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/669=qqg
- 旧物循环利用的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/spp=852
- 小区停车协商的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/iXr=G1i
- 口袋公园建设的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/754
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/gjd
- 青年志愿活动的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/hsU
- 乡村文化活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/252=vnu
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/mfs=602
- 乡村电商实践的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/d4N=k1g
- 社区活动策划的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/449
- 社区托育服务的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/ggn
- 非遗课堂体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/8dj
- 生活垃圾回收的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/037=rru
- 数字设备回收的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/lzq=954
- 数字阅读服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/W3C=Ez6
- 城市体育设施的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/644
- 社区协商议事的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/qah
- 城市基础设施的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/jba
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/474=ign
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/pug=030
- 城市生活记录的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/TpH=nFn
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/564
- 便民信息查询的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/fba
- 开放数据应用的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/TMA
- 科学运动指导的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/908=ray
- 社区便民服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/yvs=882
- 乡村阅读活动的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/Yz8=cHB
- 科学健身方法的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/560
- 家庭食品保存的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/hed
- 儿童友好空间的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/tGJ
- 公共空间导览的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/269=krw
- 市民热线服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/qnv=565
- 公园亲子设施的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/eNx=iw2
- 乡村文化空间的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/154
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/gwh
- 公共设施维护的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/Tsd
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/427=xya
- 物业服务沟通的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/pha=099
- 社区心理支持的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/hYp=wti
- 家庭理财科普的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/284
- 社区设施共享中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/yao
- 读书会组织的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/vtf
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/827=zbo
- 健康饮食教育的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/kgz=170
- 家庭节能实践中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/3Om=VCu
- 家庭防灾准备的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/821
- 城市公共座椅的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/bfe
- 家庭安全提示的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/gBz
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/996=wzx
- 城市公共厕所的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/igs=667
- 软件开发学习的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/wVb=r7S
- 公共场所导视的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/921
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/wkz
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/1PH
- 休闲运动入门的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/584=xik
- 居家适老化改造的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/bfp=799
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/s5B=DYX
- 城市公共标识的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/414
- 社区便民服务的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/rrn
- 绿色快递包装的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/BeW
- 城市应急广播的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/179=cik
- 社区艺术活动的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/zsf=820
- 乡村文化活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/IbK=vC7
- 社区绿色空间的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/709
- 社区体育组织的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/eur
- 志愿服务平台的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/3rn
- 学校体育活动的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/678=cgr
- 家庭饮食安排的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/svy=000
- 电动汽车充电的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/gTr=nmF
- 机器学习入门的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/297
- 机器人科普活动的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/anh
- 公共卫生设施的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/Qr5
- 居民健康教育的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/104=ywv
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/mwq=633
- 口袋公园建设的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/BBL=8rr
- 公共服务指南的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/719
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/swk
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/HqU
- 基层医疗预约的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/068=qin
- 家庭阅读计划的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/gbg=177
- 校园节能行动的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/z5e=aP9
- 社区艺术活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/852
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/abw
- 乡村教育资源的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/VOh
- 生活技能分享的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/232=rid
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/ppq=204
- 邻里互助活动的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/KTM=b4U
- 城市生活记录的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/336
- 社区故事采集的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/iyl
- 地方文化传播的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/jeP
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/836=nyl
- 公共空间安全的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/rdy=648
- 本地消费场景的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/Vts=IPF
- 数字创作工具的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/333
- 社区互助网络的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/xxo
- 本地旅行体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/iQQ
- 电子商务服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/731=xtl
- 公共服务指南的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/bmh=156
- 社区协商议事的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/9Os=3nB
- 居民健康教育的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/238
- 城市人文观察的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/aqv
- 城市体育设施的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/ZvR
- 家庭运动计划的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/632=vhw
- 儿童友好街区的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/wuq=713
- 节假日出行安排的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/J71=AQO
- 城市博物馆服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/678
- 灵活就业交流的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/gmi
- 科普展览体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/y7y
- 数字档案服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/200=imi
- 家庭健康管理的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/ibs=754
- 居家适老化改造的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/WCR=8uf
- 家庭节能设备的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/181
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/ywm
- 个人时间管理的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/BLp
- 节日文化体验的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/868=qfh
- 日常摄影记录的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/rjk=468
- 公共服务沟通的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/sfP=JyG
- 周末休闲规划的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/007
- 急救知识普及的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/dgb
- 青年职业探索的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/0gU
- 小区公共照明的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/353=htk
- 乡村教育资源的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/kvo=174
- 乡村电商实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/gTa=QgL
- 家庭急救准备的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/568
- 基层健康服务的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/xdy
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/236
- 便民维修服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/660=htw
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/mso=089
- 老年运动活动的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/2KC=SKG
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/910
- 家庭用电安全的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/ims
- 本地旅行体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/ake
- 社区家政服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/985=uvx
- 数字创作工具的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/zhm=189
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2?/inU=Ijy
- 数字艺术创作的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/311
- 数字生活课堂的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/whq
- 社区应急准备的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/Pq4
- 乡村文化活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/710=rfi
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/cwq=907
- 城市公共标识的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/8hT=77h
- 城市公共艺术的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/229
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/uyp
- 社区宠物管理的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/d6g
- 社区文化传播的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/380=frp
- 城市社区治理的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/eho=632
- 科学教育活动的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/JWB=WC5
- 生成式工具使用的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/924
- 社区设施共享的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/tua
- 科学信息获取的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/9Tx
- 乡村文化活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/217=otk
- 城市公共饮水的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/joz=948
- 城市雨天出行的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/FXX=kLd
- 公共图书馆服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/101
- 社区便民服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/mzt
- 社区消防演练的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/SCn
- 数字课堂应用的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/651=eyh
- 社区便利生活的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/chj=273
- 家庭理财科普的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/pvX=kXx
- 地方旅游导览的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/975
- 机器人科普活动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/bbm
- 课后服务体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/YLX
- 节约用水实践的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/075=pxw
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/lxf=463
- 城市人文观察的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/H2G=qMi
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/033
- 网络安全教育的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/wyb
- 老年友好服务的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/Y5u
- 城市社区治理的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/665=wtr
- 社区绿色空间的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/wyd=290
- 老年学习活动的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/MOZ=kja
- 应急物资管理的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/020
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/liv
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/Pw0
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/353=qnh
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/jhs=925
- 个人信息保护的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/bSC=fHl
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/730
- 城市社区治理的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/xbm
- 数字资源检索的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/y8q
- 运动安全知识的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/710=cie
- 社区科普课堂的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/sur=726
- 校园节能行动的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/uzW=elA
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/314
- 软件开发学习的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/hse
- 数字便民地图的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/o5n
- 智慧停车服务的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/507=buc
- 公共空间照明的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/pou=146
- 人工智能科普的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/WKU=ASO
- 租房信息服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/532
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/rbq
- 城市住房服务中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/ec1
- 社区应急准备的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/770=bev
- 居民健康教育的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/lnw=181
- 城市共享单车的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/rq9=wSj
- 电子商务服务的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/691
- 家庭安全提示的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/hvm
- 家庭理财科普的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/Khb
- 社区便民集市的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/604=rfb
- 运动安全知识的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/iee=429
- 职业技能学习的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/fN4=9ri
- 城市应急科普的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/185
- 公共空间休憩的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/nmc
- 社区艺术活动的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/V24
- 城市社区治理的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/552=wgr
- 社区儿童活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/wqx=415
- 家庭健康管理的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/RT8=KvS
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/300
- 文化讲座服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/cxx
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/uWB
- 公共服务沟通的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/360=agf
- 公交站点体验的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/crk=309
- 家庭消费规划的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/BFB=k10
- 基层医疗预约的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/006
- 数字艺术创作的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/uow
- 数字创意课程的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/nmj
- 家庭饮食安排的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/273=iuo
- 城市公共空间的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/kwt=161
- 数字课堂应用中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/SCz=JNW
- 生成式工具使用的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/835
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/dpg
- 个人信息保护的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/pH8
- 基层医疗预约的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/929=gzy
- 公共设施使用的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/igv=542
- 本地消费场景的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/82B=vwS
- 社区便民集市的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/362
- 社区环保活动的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/kwe
- 课后服务体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/ice
- 公共服务沟通的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/721=sax

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
