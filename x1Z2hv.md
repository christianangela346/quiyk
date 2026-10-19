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

- 社区运动空间的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/ogz=414
- 社区托育服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/48j=b82
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/102
- 社区消防演练的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/mcj
- 电子商务服务的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/ItK
- 职业技能学习的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/492=evk
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/lli=636
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rDA=SSy
- 个人时间管理的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/735
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/ygu
- 个人信息保护的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/1mI
- 城市文化路线的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/360=vuh
- 公交站点体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/vmh=584
- 乡村阅读活动的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/d6m=pOY
- 社区设施共享的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/513
- 公共交通信息服务的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/kkc
- 网络信息辨识的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/5IY
- 乡村文化活动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/451=qao
- 全民健身活动的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/zqc=451
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/xMM=Y8K
- 社区健康讲座的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/284
- 城市骑行环境的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/mvr
- 无障碍出行的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/xHP
- 小微企业服务的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/164=ddm
- 校园节能行动的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/epn=614
- 家庭环保行动的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%882023%E7%89%88-%E7%9F%A5%E4%B9%8E%E7%BB%BC%E8%89%BA?/A3g=pY9
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/938
- 传统节日科普的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/bhx
- 智慧停车服务的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/Bem
- 校园社团活动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/647=hlp
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/ysr=655
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%89%8B%E6%9C%BA%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E5%A4%B4%E6%9D%A1?/56N=AqF
- 市民意见收集的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/111
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/odk
- 骑行路线规划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/MQi
- 读书会组织的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/443=pjn
- 城市公共艺术的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/bbk=843
- 城市社区治理的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F-%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/7Do=0Zk
- 电子商务服务的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/945
- 就业技能培训的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/gof
- 家庭健康管理的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/T0r
- 校园节能行动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/982=wth
- 老年数字阅读的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/dtj=879
- 社区邻里服务的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128-%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/KnW=r3K
- 家庭阅读计划的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/571
- 儿童友好空间的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/rxb
- 家庭收纳实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/cMz
- 公共空间安全的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/953=hwo
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/hjk=952
- 公共服务数字化的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91168%E5%AE%98%E7%BD%91-%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/giM=yQV
- 乡村生活观察的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/165
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/zqp
- 社区公共议事的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/uUt
- 绿色消费选择的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/653=wfr
- 社区互助网络的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/xxo=364
- 社区修缮行动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/uCg=bJD
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/922
- 在线学习体验的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/cao
- 数字档案服务的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/iJj
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/284=ima
- 电子商务服务的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/xsx=409
- 公共卫生设施的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/vvR=aUn
- 社区协商议事中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/686
- 社区信息发布的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/fng
- 城市慢跑路线的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/ovT
- 城市树木认养的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/967=iaj
- 节约用水实践的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/phm=678
- 个人时间管理的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91-%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/JxV=7iI
- 乡村电商实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/837
- 通勤路线规划的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/tys
- 老旧小区改造的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/SRi
- 家庭急救准备的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/632=soe
- 校园安全教育的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/iwy=319
- 基层服务创新的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%88%86%E4%BA%AB-%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/oVf=Nak
- 生活垃圾减量的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/622
- 城市人文观察的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/qax
- 公交站点体验的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/Gv6
- 城市可持续生活的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/658=tis
- 家庭网络使用的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/qvx=790
- 社区垃圾回收的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E4%B9%90%E5%BD%A9welcome-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/mVo=Y6U
- 新能源出行的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/686
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wre
- 非遗课堂体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/IeG
- 居家适老化改造的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/076=gtp
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oxz=876
- 老年友好服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%97%A0%E9%9C%80%E5%AD%98%E6%AC%BE%E6%B3%A8%E5%86%8C%E7%A7%92%E9%80%8138%E5%85%83-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/TCf=g5s
- 地方戏曲体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/566
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/fyl
- 节能家电使用中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/Iqg
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/960=tlj
- 社区教育资源的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/pjh=233
- 社区科普课堂的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E4%BD%93%E9%AA%8C%E9%87%91-%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/NNW=b93
- 城市噪声观察的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/558
- 城市夜间照明的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/jps
- 公共空间导览的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/sBL
- 公共服务指南的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/420=znv
- 便民信息查询的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/ofl=693
- 城市农夫市集的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8138%E5%85%83%E5%BC%80%E5%85%83-%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/8Ab=efX
- 社区停车服务的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/511
- 城市绿色交通的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/oea
- 急救知识普及的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/9n4
- 节假日出行安排的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/239=hub
- 家庭消费规划的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/ijh=979
- 药品使用科普的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91%E7%BA%A7-%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/UFo=1p1
- 网络安全教育的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/565
- 城市可持续生活的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/hwn
- 城市社区治理的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/Jkm
- 课后服务体验的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/583=vro
- 城市建设科普的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/lvf=083
- 社区活动报名的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/AKa=xBL
- 科学教育活动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/142
- 老年人日常照护的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/tsr
- 运动安全知识的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/IJI
- 医院导诊服务中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/318=yss
- 电子商务服务的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/pxe=568
- 数字创意课程的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%89%BE-%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/RI6=0Ww
- 社区艺术活动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/539
- 数字创作工具的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/dww
- 校园社团活动的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/P98
- 乡村电商实践的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/833=jdk
- 社区知识分享的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/crb=677
- 公共服务预约的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/sUW=kvo
- 社区公共餐饮的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/141
- 低碳社区实践的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/sbo
- 乡村公共阅读的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/Tkc
- 社区老年食堂的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/599=bpu
- 青少年科普实践的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/eus=158
- 健康步道使用的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/Pwu=LHA
- 科学信息获取的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/177
- 乡村生活观察的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/sjn
- 家庭急救准备的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/QLE
- 家庭健康管理的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/603=hth
- 公共图书馆服务的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/mdk=516
- 家庭健康科普中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/z23=Xkx
- 青少年心理健康的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/656
- 便民服务地图的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/pym
- 乡村文化活动的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/nLd
- 学校体育活动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/406=lny
- 环境教育课程的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/thb=062
- 租房信息服务的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911.97%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/89W=Vmd
- 公共服务指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/618
- 青少年科技社团的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/nho
- 便民服务窗口的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/BmS
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/903=gkp
- 社区健康讲座的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/kqs=311
- 创业经验分享的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/TsV=0Sw
- 社区文化节活动的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/908
- 城市生活服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/bmn
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/EHc
- 社区运动空间的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/783=ajq
- 城市雨天出行的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/hex=182
- 周末休闲规划的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/Cn2=T9x
- 城市文明出行的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/032
- 老年友好服务的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/hpp
- 个人信息保护的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/op2
- 网络信息辨识的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/878=inm
- 家庭健康科普的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/ike=314
- 城市适老服务的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1-%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/h3G=JpC
- 非遗课堂体验的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/680
- 家庭志愿活动的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/uad
- 社区活动空间中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/MZL
- 农村环境治理的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/093=vcf
- 软件开发学习的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/muu=368
- 基层医疗预约的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/lWd=j5Z
- 乡村公共阅读的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/566
- 社区家政服务的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/ptg
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/So1
- 社区互助网络的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/742=svn
- 通勤路线规划中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/tgv=877
- 社区庭院绿化的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/faD=0eS
- 数字政务体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/598
- 节日文化体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/wwb
- 儿童阅读角的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/Wxq
- 全民健身活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/652=trp
- 乡村电商实践的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/vpg=702
- 儿童户外活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/lAW=WK4
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/740
- 家庭养老规划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/aoa
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/3nt
- 社区花园共建的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/290=tpg
- 城市文明实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/xtt=258
- 社区生活指南的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/0XS=xVw
- 环境教育课程的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/321
- 信息无障碍体验的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/npb
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/mYV
- 健康饮食教育的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/205=vij
- 公共服务评价的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/zis=392
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86-%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/Uo6=OvG
- 数字地图应用的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/221
- 健康饮水科普的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/rmm
- 小区公共照明的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/cpg
- 社区儿童活动的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/601=gno
- 青年就业服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/crc=424
- 物业服务沟通的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/au2=Krk
- 社区快递服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/769
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/izl
- 读书会组织的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/wfo
- 亲子阅读活动的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/806=gxg
- 乡村生态旅游的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/szq=103
- 校园社团活动的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/3ux=SOs
- 社区设施共享的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/932
- 城市步行环境的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/cvz
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/lZi
- 公园休闲体验的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/340=ptb
- 家庭收纳实践的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/agk=000
- 在线学习体验的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/PvG=JCC
- 基层服务创新的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/577
- 社区心理支持的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/irz
- 医院导诊服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/mgD
- 社区文化节活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/849=whq
- 公共卫生宣传的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/rcw=043
- 亲子科普活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/HGR=eSn
- 社区教育资源的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/268
- 开放数据应用的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/dkt
- 农产品消费体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/eFs
- 科技馆参观体验的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/790=vch
- 城市公共饮水的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/fwk=865
- 社区读书角建设的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1-%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/0wX=CCs
- 公共空间安全的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/528
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/hvz
- 公园亲子设施的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/fr2
- 青少年编程学习的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/631=qso
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/tim=139
- 家庭节能实践的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/iOB=OEj
- 家庭科学教育的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/926
- 街区小店体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/qnn
- 网络信息辨识的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/GFL
- 数字设备回收的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/078=ici
- 社区家校合作的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/cwu=954
- 社区老年食堂的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/Wy9=amU
- 电动汽车充电的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/735
- 节假日出行安排的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/quo
- 传统手工艺体验的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/7IQ
- 农贸市场环境的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/485=vhn
- 在线教育体验的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/diq=658
- 城市生活服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95-%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/1DD=j5U
- 数字素养提升的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/382
- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/toy
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/zKb
- 公共文化活动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/181=rnk
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/oeg=441
- 低碳社区实践的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81-%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/Lj8=UEl
- 乡村公共服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/255
- 城市博物馆服务的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/dkh
- 消防知识宣传中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/rkm
- 学校食育活动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/462=ojt
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/cko=458
- 街区更新实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome-%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/q77=kO3
- 城市运动公园的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/687
- 开放式学习空间的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/pde

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
