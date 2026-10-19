# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/0wd
- 乡村公共文化的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/688=gak
- 社区知识分享的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/xnm=454
- 社区志愿服务的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/gZm=c3f
- 公交站点体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/759
- 城市可持续生活的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/bya
- 城市公共厕所的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/JtI
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/248=jec
- 城市应急广播中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/pie=190
- 社区儿童活动的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/NtA=3YZ
- 节能家电使用的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/756
- 休闲运动入门的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/eps
- 学校食育活动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/8mN
- 城市文明实践的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/906=rup
- 劳动教育实践的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/wds=977
- 城市慢行系统的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/54m=7w1
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/359
- 环境教育课程的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/riy
- 读书会组织的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/o2p
- 社区儿童活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/989=kkh
- 基层健康档案的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/hmr=978
- 基层健康档案的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/0iZ=awf
- 青年职业探索的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/828
- 社区文化传播的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/ypr
- 光伏知识科普的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/L6j
- 社区消防演练的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/653=xac
- 青少年编程学习的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/zhp=806
- 城市公共空间的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/U3G=zvH
- 青少年编程学习的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/785
- 数字课堂应用的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/bjn
- 本地历史资料中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/xe6
- 网络安全教育的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/709=gki
- 儿童友好街区的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/igp=336
- 智能家居应用的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/3Mz=WJC
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/192
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/kmh
- 社区垃圾回收的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/rTO
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/991=gck
- 家庭志愿活动的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/yqj=434
- 社区健康讲座的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E9%9B%85%E8%99%8E%E7%9B%B4%E6%92%AD?/rON=33p
- 社区生活指南的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/403
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/inq
- 社区心理支持的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/gnT
- 社区读书角建设的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/619=stz
- 信息无障碍体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/zkg=786
- 社区应急准备的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_36%E6%B0%AA%E6%88%B7%E5%A4%96?/Iy9=D94
- 社会体育指导的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/399
- 社区便民集市的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/nzy
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/Guh
- 城乡公共服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/758=djl
- 社区儿童活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/pja=809
- 乡村文化空间的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/PfP=WcF
- 健康步道使用的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/318
- 老年人日常照护的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/srn
- 儿童户外活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/hjx
- 科技馆参观体验的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/310=wnf
- 读书会组织的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/iwv=940
- 口袋公园建设的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/od9=dAQ
- 居家适老化改造的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/842
- 志愿者培训交流的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/fmz
- 城乡公共服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/yf7
- 城市社区治理的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/522=gfk
- 远程协作工具的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/hxz=930
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/dgN=z8u
- 文明养宠科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/978
- 节气饮食文化的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/eek
- 公共服务指南的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/Ljl
- 社区手工活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/946=rye
- 青少年编程学习的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/vjz=692
- 社区便民集市的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/Hgr=q1m
- 市民热线服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/285
- 儿童运动体验的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/ako
- 家庭环保行动的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/JIS
- 数字地图应用的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/474=jlf
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/jzo=358
- 社区菜市场服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/IO1=Kvl
- 学校体育活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/639
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/vin
- 创业经验分享的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/qef
- 节气饮食文化中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/058=nlb
- 节气饮食文化的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/ajq=826
- 公共交通信息服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/paP=6P7
- 公共文化活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/418
- 城市步行友好的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/vsn
- 气象科普传播的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/92F
- 应急物资管理的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/380=geg
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/ket=412
- 无障碍信息设计的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Fh9=zOj
- 小区停车协商中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/139
- 公共服务预约的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/zvz
- 家庭饮食安排的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/1dB
- 社区公共议事的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/213=zpt
- 社区花园共建的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/iut=340
- 户外活动组织的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E8%A6%81%E9%97%BB?/SCB=BwR
- 家庭网络使用的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/740
- 节假日出行安排的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/kcz
- 终身学习资源的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/swO
- 节日文化体验的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/719=ccb
- 智能家居应用的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/wwo=327
- 机器人科普活动的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/J3Z=hKJ
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/048
- 社区心理支持的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/emg
- 老年友好服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/ImD
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/936=fdp
- 家庭收纳实践的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/dse=690
- 周末休闲规划的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/zZa=NNh
- 市民热线服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/251
- 租房信息服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/ypv
- 公共服务数字化的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/LPp
- 城市公共空间的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/317=pnh
- 人工智能科普的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/swl=916
- 城市适老服务的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/5pn=fYB
- 城市地名文化的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/832
- 城市公共标识的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/bsu
- 城市游园体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/gwa
- 终身学习资源的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/344=sov
- 社区便民服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/pgk=326
- 节约用水实践的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/vdY=sMc
- 社区手工活动的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/423
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/tow
- 城市博物馆活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/0um
- 乡村公共文化的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/616=lwd
- 社区庭院绿化的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/faz=344
- 地方民俗记录的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/OUs=ZuE
- 节能生活方式的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/090
- 城市空气科普的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vkf
- 基层医疗预约的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qzY
- 社区科普课堂的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/312=rku
- 全民阅读推广的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/njr=195
- 城市噪声观察的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Fvp=tNI
- 亲子阅读活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/355
- 环境教育课程的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/xbv
- 数字课堂应用的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/cdE
- 软件开发学习的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/004=tey
- 骑行路线规划的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/spb=195
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/r5S=moH
- 社区协商议事的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/167
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/eyw
- 低碳社区实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/rO6
- 家庭防灾准备的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/622=hib
- 城市夜间照明的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/rey=264
- 农产品消费体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/89j=CPZ
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/170
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/uaj
- 乡村公共服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/hRO
- 地方戏曲体验的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/329=zln
- 科学教育活动的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/cqs=380
- 便民服务地图的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/3Lo=OIV
- 乡村教育资源的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/991
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/dgi
- 社区艺术活动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/DLS
- 社区邻里服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/696=xcp
- 生成式工具使用的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/bbe=126
- 社区知识分享的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/eTY=zLO
- 家庭急救准备的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/736
- 社区活动策划的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/poi
- 文化场馆预约的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/Cwr
- 青少年户外教育的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/878=vec
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/yko=955
- 社区家校合作的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/1gJ=Tpp
- 青年就业服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/302
- 校园节能行动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/emg
- 居民健康教育的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/pYP
- 市民意见收集的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/743=fth
- 城市树木认养的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/qul=693
- 课后服务体验的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/jCV=VDt
- 老旧小区改造的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/044
- 数字支付体验的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/zrx
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/yqm
- 城市步行环境的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/774=wsp
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/rxc=634
- 城市应急广播的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/2gh=6so
- 社区读书角建设的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/903
- 社区法律科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/arj
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/4Qh
- 市民热线服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/036=ilz
- 开放数据应用的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/fue=027
- 城市公共厕所的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/EXE=m5R
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/586
- 城市便民驿站的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/nqj
- 地方民俗记录中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/trk
- 青年就业服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/577=zcc
- 社区家校合作的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/etw=414
- 家庭养老规划的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/MX2=YlJ
- 家庭食品保存的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/889
- 社区手工活动的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/yro
- 科学观察活动的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/AXf
- 节约用水实践的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/783=noj
- 绿色生活实践的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/iwd=362
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/5vl=TUY
- 健康信息获取的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/944
- 社区修缮行动的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/yna
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/jQn
- 城市适老服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/529=eup
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/jxq=879
- 社区设施共享的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/MWW=FSa
- 绿色消费选择的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/182
- 市民热线服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/jod
- 读书会组织的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/Mev
- 科学信息获取的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/539=hvv
- 劳动教育实践的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/jds=182
- 公共场所导视的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/KZV=UqL
- 城市雨天出行的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/082
- 家庭收纳实践的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/msj
- 城市生活记录的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/NaY
- 乡村阅读空间的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/636=dsd
- 基层服务创新的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/uni=594
- 节气饮食文化的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/xQo=SAl
- 社区故事采集的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/725
- 公共设施使用的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/dza
- 城市可持续生活的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/65M
- 科学健身方法的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/247=dmu
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/kxl=036
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/lLP=bwp
- 家庭环保行动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/762
- 文化讲座服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/wnq
- 软件开发学习的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/Cgj
- 家庭养老规划的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/804=was
- 社区便民服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/yrg=965
- 数字素养提升的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/ijd=kMu
- 老年数字阅读的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/714
- 城市夜间照明的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/bvd
- 社区菜市场服务的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/dIt
- 社区停车服务的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/802=kqg
- 社区文化传播的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/ekt=112
- 农村环境治理的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/p8q=eco
- 社区教育资源的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/531
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/pcj
- 城乡公共服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/Js0
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/808=bnb
- 绿色生活实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/hpb=646
- 节假日出行安排的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/gam=VAJ
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/556
- 人工智能科普的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/zuz
- 家庭安全提示的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/BoU
- 社区便民集市的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/089=prs
- 公园休闲体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/krd=809
- 公共交通接驳的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/v63=KZx
- 公共空间照明的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/903
- 个人信息保护的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/vrg
- 家庭健康科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/IV3
- 社区互助网络的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/581=jji
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/qkp=538
- 校园安全教育的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/sgV=kLB
- 医院导诊服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/853
- 城市生活服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/itw
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/GGN
- 社区知识分享的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/771=xzj
- 社区共享书架的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/wji=810
- 社区修缮行动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDAPP_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/qRu=I2a

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
