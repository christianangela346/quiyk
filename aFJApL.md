# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/642
- 居民健康教育的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/hlx
- 药品使用科普的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ZKt
- 家庭急救准备的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/619=vvs
- 便民服务窗口的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/vkk=162
- 城市文化路线的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97%E4%BA%BA-%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/6NC=4OR
- 校园社团活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/368
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/siy
- 社区环保活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/zs1
- 城市绿色交通的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/370=xpz
- 节能家电使用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/tin=080
- 周末休闲规划的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BE%AE%E8%81%8A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/ZKe=jmz
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/705
- 家庭网络使用的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/gtz
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/Uzp
- 社区家政服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/257=yqb
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/zfu=429
- 老年人文化生活的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BB%80%E4%B9%88%E6%98%AF%E5%BE%AE%E8%81%8A-%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/qWZ=QpU
- 家庭食品保存的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/261
- 城市文明出行的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/dxs
- 社区修缮行动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/Cpl
- 开源技术交流的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/174=ytd
- 城市运动公园的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/vkz=951
- 邻里互助活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92app%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/eFm=juV
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/862
- 公共健身器材的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/cxk
- 数字地图应用的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/dES
- 城市文明出行的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/729=adi
- 周末休闲规划的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/zun=361
- 城市人文观察的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/XXB=DIk
- 数字档案服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/585
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/dis
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/vOd
- 城市骑行环境的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/878=lyd
- 绿色校园实践的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/kon=435
- 社区便民服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E5%93%94%E5%93%A9%E9%80%9F%E8%A7%88?/OFv=KY6
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/649
- 绿色消费选择的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/nik
- 城市可持续生活的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/yql
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/946=oik
- 远程协作工具的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/zze=284
- 公共服务评价的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/1rX=wy6
- 校园节能行动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/393
- 基层医疗预约的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/bwg
- 个人时间管理的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/CJp
- 家庭志愿活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/283=uss
- 社区体育组织的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/vda=335
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91-%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/SsY=ql9
- 科学健身方法的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/396
- 家庭用电安全的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/yvh
- 食品安全科普的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/uGN
- 社区健康讲座的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/831=vge
- 城市微更新实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/opd=438
- 城市体育设施的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll--%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9-%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/X4W=1xQ
- 社区停车服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/433
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/ihh
- 开放数据应用的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/ceb
- 社区宠物管理的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/215=oue
- 儿童户外活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/avs=090
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%9B%BD%E4%B8%AD%E5%BD%A9%E7%BD%91%28%E5%AE%98%E7%BD%91%29-%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/5AC=CX8
- 低碳社区实践的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/207
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/cdr
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/T4L
- 城市休闲步道的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/800=tee
- 社区学习活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/okz=169
- 农贸市场环境的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evl%E7%BD%91%E9%A1%B5-%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/gAr=gFR
- 物业服务沟通的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/927
- 城市文化路线的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/hll
- 公交站点体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/Fuu
- 街区小店体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/340=ixb
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/cjv=626
- 社区设施共享的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%A8%A1%E6%8B%9F%E6%9C%BA%E5%8F%B7%E4%BB%8A%E5%A4%A9-%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/K1P=KCg
- 绿色校园实践的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/474
- 家庭节能设备的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/rqg
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/LM1
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/214=cen
- 本地历史资料的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/chq=731
- 城市夜间照明的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E9%80%9A%E6%8B%BC%E6%90%8F%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/dqb=3iL
- 城市基础设施的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/761
- 市民意见收集的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/tuo
- 老年人文化生活的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/rrd
- 数字课堂应用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/379=luz
- 家庭网络使用的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/iac=465
- 节日文化体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evii%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93D%E4%BB%8A%E5%A4%A9-%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/eCp=hpt
- 城市文明实践的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/549
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/xth
- 社区便利生活的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/HUi
- 健康饮食教育的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/526=nic
- 家庭安全提示的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/mcu=180
- 社区便利生活的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B9%8B%E9%A6%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F-%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/Cmh=PHP
- 老年数字阅读的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/520
- 社区教育资源的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/vek
- 文化讲座服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/6Kb
- 市民热线服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/131=ovb
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/jda=407
- 地方民俗记录的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/onD=ozE
- 农村环境治理的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/108
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/rzy
- 家庭运动计划的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/t0L
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/487=ieb
- 线上阅读资源的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/kyp=041
- 农贸市场环境中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/6Xx=Ef2
- 城市慢行系统的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/337
- 基层健康服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/ckp
- 就业技能培训的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/som
- 图书借阅体验的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/320=lvs
- 志愿服务平台的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/zwa=732
- 青少年户外教育的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/WrJ=Bfe
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/598
- 城市骑行环境的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/rqu
- 读书会组织的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/sVd
- 本地旅行体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/393=rfw
- 社区志愿服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/gig=801
- 光伏知识科普的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/WW2=gCH
- 数字课堂应用的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/950
- 数字阅读服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/gag
- 公交站点体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/bVy
- 城市便民驿站的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/624=ghz
- 社区志愿服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/mln=620
- 基层健康档案的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E1.0-%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/Gn6=smu
- 社区体育组织的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/982
- 家庭照护支持的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/rdl
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/JpI
- 社区文化传播的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/157=fdc
- 城市步行友好的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/ale=120
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88-%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/Vrb=5YA
- 街区道路维护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/031
- 乡村阅读空间的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/gkz
- 青年职业探索的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/oAo
- 光伏知识科普的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/022=mdd
- 社区手工活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/mas=167
- 社区信息发布的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/P1n=sik
- 社会体育指导的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/477
- 基层健康档案的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/mpy
- 生活技能分享的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/vQa
- 社区教育资源的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/991=kcl
- 家庭节能实践的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/eqo=229
- 口袋公园建设的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/nVQ=qZg
- 开放式学习空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/855
- 在线教育体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/ikc
- 城市运动公园的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/Vln
- 儿童友好街区的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/611=qff
- 老年运动活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/ine=059
- 乡村生活观察的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/bu4=FLG
- 科学健身方法的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/330
- 跨代沟通活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/okj
- 数字档案服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/ony
- 社区环保活动的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/779=pfv
- 文化讲座服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/yqq=464
- 农业科普体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/tUg=y4R
- 数字支付体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/730
- 老年运动活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/rew
- 绿色消费选择的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/q8d
- 绿色快递包装的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/515=rew
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/rdb=859
- 公共场所导视的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/E52=eJC
- 青少年科技社团的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/181
- 科学信息获取中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/efi
- 公园休闲体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/Vl3
- 社区科普课堂的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/899=tmh
- 社区消防演练的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/jfw=527
- 社区故事采集的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/2rf=cCs
- 读书会组织的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/954
- 社区停车服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/ukg
- 公共空间安全中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/0gM
- 家庭环保习惯的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/171=ymw
- 科学教育活动的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/til=142
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/gL1=j4b
- 智能手机助老中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/377
- 居民健康教育的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/lwk
- 城市步行环境中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/2lf
- 家庭科学教育的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/809=zmr
- 城市公共座椅的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/gvu=803
- 旧物循环利用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/kWk=ZPZ
- 开源技术交流的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/255
- 街区绿化养护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/jnb
- 社区防暑服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/EiQ
- 城市博物馆服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/516=ieh
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/hfe=493
- 城市游园体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/llf=thP
- 老旧小区改造的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/638
- 城市公共艺术中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/raj
- 家庭安全提示的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/bu6
- 社区绿色空间的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/089=tzj
- 健康步道使用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/xfw=122
- 城市骑行环境的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/9ht=np8
- 公共空间导览的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/536
- 社区环保活动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/fvs
- 城市文明出行的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/gQV
- 街区小店体验的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/791=jku
- 邻里共享空间的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/whx=749
- 城市慢行系统的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/VPn=6b4
- 青少年心理健康的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/329
- 社区交通安全的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/lnv
- 垃圾分类指导的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/eCL
- 基层健康档案的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/192=nsp
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/ibj=870
- 本地历史资料的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/F54=B2W
- 公园亲子设施的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/104
- 儿童户外活动的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/uxq
- 数字资源检索的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/6Vw
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/134=sqw
- 绿色生活实践的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/rru=970
- 家庭消费规划的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9C%E4%B8%9A?/Suw=yF3
- 生活垃圾回收的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/889
- 绿色快递包装的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/nkc
- 灵活就业交流的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/VdT
- 绿色办公实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/853=jgk
- 课后服务体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ivp=711
- 农产品消费体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/DIQ=jBl
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/236
- 校园社团活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/izj
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/lcm
- 社区信息发布中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/717=cgj
- 城市公共座椅的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/aza=470
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/9zE=g8l
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/461
- 城市文明实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/keu
- 智能家居应用的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/0YW
- 儿童友好街区的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/923=kpu
- 就业技能培训的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/ddk=612
- 乡村文化空间的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/00Y=Huv
- 数字创意课程的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/667
- 乡村阅读空间的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/eme
- 健康饮食教育的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/9jG
- 社区健康讲座的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/658=uke
- 青年志愿活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/kda=318
- 数字支付体验的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/Lrq=NhY
- 社区活动策划的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/241
- 家庭节能实践的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/rji
- 数字阅读服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/YEV
- 城市骑行环境的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/043=ciw
- 数据分析入门的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/ama=640
- 基层健康服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/zdP=OYu
- 基层医疗预约的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/791
- 公共健身器材的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/tnz
- 市民意见收集的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/eSB
- 城市便民驿站中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/660=jvk
- 乡村产业科普的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/hld=681
- 城市农夫市集的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/DdZ=0jp
- 儿童户外活动的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/269
- 社区休闲设施的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/gzi
- 旧物循环利用中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/O18
- 家庭健康管理的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/243=suw
- 城市噪声观察的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/vos=343
- 旧物循环利用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/2ej=Y37
- 家庭养老规划的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/530
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/dzy
- 社区心理支持的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/6hX
- 绿色出行服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B-%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/202=eau

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
