# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 社区设施共享的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25-%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/S7P
- 儿童运动体验的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25-%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/314=cdw
- 城市空气科普的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25-%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/wfa=578
- 社区文化节活动的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25-%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/5Do=Fr1
- 旧物循环利用的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/657
- 数字地图应用的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/yfr
- 图书借阅体验的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/OAl
- 科学运动指导中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/678=szp
- 居家适老化改造的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/gus=504
- 公共服务咨询的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA-%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/qQG=bS3
- 数字便民地图的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/561
- 农产品消费体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/vjt
- 城市噪声观察的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Lnf
- 公共卫生设施的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/052=gek
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/kly=563
- 休闲运动入门的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92-%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/kr9=bGM
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/672
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/alf
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/BDM
- 骑行路线规划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/816=fgs
- 小微企业服务的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/lbp=547
- 城市微更新实践的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/eLD=MeJ
- 公共场馆服务的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/819
- 社区安全巡查的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/qya
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/P95
- 社区公共卫生的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/519=vsl
- 数字创作工具的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/bat=514
- 课后服务体验的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-36%E6%B0%AA%E8%A7%A3%E5%AF%86?/v4x=7Zr
- 亲子科普活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/124
- 城市空气科普的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/alc
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/j3Q
- 新能源知识普及的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/874=mfh
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/kym=362
- 老年人日常照护的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86-%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/ljX=Xzz
- 城市噪声观察的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/349
- 公共空间安全的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/ltx
- 家庭阅读计划的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/gb1
- 社区阅读服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/127=ijl
- 数字阅读服务的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/hae=430
- 绿色消费选择的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC-%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/wLt=tu4
- 社区手工活动的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/581
- 家庭收纳实践的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/pwz
- 基层健康服务的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/wjL
- 校园社团活动的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/242=zxd
- 老年人出行服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/udr=631
- 环境教育课程的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD-%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/ksQ=dGq
- 健康饮水科普的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/974
- 城市应急科普的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/igm
- 乡村产业科普的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/yOW
- 乡村阅读空间的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/929=wzq
- 社区便民服务的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/tcw=745
- 乡村电商实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95-%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/kc1=ZVs
- 数字艺术创作的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/636
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/qyb
- 社区文化传播的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/8QW
- 乡村公共文化的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/510=yho
- 亲子阅读活动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/zwe=185
- 青年职业探索的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/Lxq=3lB
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/536
- 环境监测科普的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/loi
- 社区便民集市的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/ZpQ
- 小区停车协商的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/091=yov
- 公共卫生宣传的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/dld=232
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8-%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/Pep=EuL
- 环境监测科普的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/338
- 乡村公共服务的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/lqv
- 新能源知识普及的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/YR2
- 城市公共标识中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/804=pgz
- 公共卫生设施的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/kez=717
- 开放数据应用的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/473=Fo9
- 街区小店体验的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/155
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/pfj
- 城市文明实践的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/9MK
- 儿童户外活动的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/003=fzi
- 小区公共照明的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/iiw=087
- 低碳社区实践的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/gy5=oSE
- 电子商务服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/338
- 公共卫生宣传的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/lkz
- 无障碍信息设计的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/7xd
- 城市博物馆活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/612=kqi
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/zny=665
- 社区教育资源的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95-%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/YUk=Ld7
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/517
- 家庭急救准备的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/qrj
- 生活服务数字化的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/2ow
- 文化场馆预约的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/397=ynn
- 城市休闲步道的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/eql=158
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0-%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/gb9=IcF
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/684
- 市民热线服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/ivc
- 社区文化传播中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/ukX
- 家庭运动计划的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/131=ejc
- 城市基础设施的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/wsh=648
- 公共交通接驳的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/0j1=htL
- 社区志愿服务的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/799
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/pcc
- 儿童安全出行的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Euy
- 社区运动空间的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/934=zaj
- 开放数据应用的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/jlg=132
- 城市空气科普的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97-%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/ZRR=RU5
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/553
- 青少年户外教育的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/xql
- 数字学习资源的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/eT2
- 农产品消费体验的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/825=ifi
- 乡村文化空间的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/spd=392
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/bpK=rVB
- 城乡交流活动的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/547
- 农产品消费体验的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/dll
- 数字艺术创作的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/aNn
- 职业技能学习中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/292=fha
- 城市应急科普的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/qtd=967
- 乡村公共阅读的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95-%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/hva=hma
- 城市社区治理的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/937
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/utj
- 老旧小区改造的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/epd
- 食品安全科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/616=aff
- 城市步行环境的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cfx=319
- 智慧停车服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8-%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/lD0=dIp
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/275
- 老年学习活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/yte
- 社区法律科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/aSM
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/546=crt
- 城市夜间生活的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/ofo=465
- 口袋公园建设的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/z3N=8Sr
- 数字资源检索的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/694
- 社区休闲设施的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/vyf
- 在线学习体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rLo
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/239=tgm
- 青年职业探索的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/agk=013
- 街头绿植养护的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/3Ty=ail
- 家庭消费规划的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/539
- 街区道路维护的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/aae
- 城市住房服务的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/agf
- 科学观察活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/332=lsw
- 城乡交流活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/gwo=550
- 市民热线服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/7cm=YwW
- 城市可持续生活的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/733
- 社区心理支持的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/zve
- 乡村文化活动的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/Ws2
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/413=yzt
- 乡村文化活动的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/qil=278
- 地方旅游导览的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/FZO=C7H
- 通勤路线规划的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/773
- 城市博物馆服务的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/lek
- 健康步道使用的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/Nv9
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/818=qxu
- 志愿服务平台的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/gcd=514
- 社区活动策划的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%2C%E5%90%88%E6%B3%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/HMs=0qg
- 家庭用电安全的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/066
- 公共图书馆服务的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/qdy
- 城市文明实践的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/ZQR
- 周末休闲规划的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/396=smi
- 老旧小区改造的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/bsa=847
- 乡村电商实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%BF%83%E5%8A%A8%E7%9B%B4%E6%92%AD-%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/ISX=MpE
- 城市住房服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/963
- 社区休闲设施中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/rsq
- 社会体育指导的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/j8V
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/380=zse
- 城市雨天出行的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/kbz=331
- 城市文明出行的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/8bx=MCP
- 绿色建筑理念的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/926
- 城市噪声观察的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/fbo
- 农业科普体验的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/iEt
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/920=bap
- 开源技术交流的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/tum=340
- 社区防暑服务的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%A7%86%E9%A2%91-%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/Ul9=xPs
- 健康饮水科普的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/674
- 本地消费场景的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/hoy
- 城市游园体验的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/R73
- 社区老年食堂的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/381=dbh
- 城市便民驿站的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/vcn=156
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/lwy=UOl
- 市民意见收集的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/843
- 开源技术交流的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/ikr
- 基层健康档案的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/py7
- 青少年心理健康的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/271=xpw
- 数字课堂应用的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/fiq=084
- 家庭运动计划的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/mGO=uCD
- 家庭安全提示中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/648
- 城市社区治理的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/rlv
- 绿色校园实践的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/vFw
- 社区便民集市中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/669=mcx
- 数字创意课程的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/nwy=187
- 城市雨天出行的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E4%B9%85%E4%B9%85%E4%B9%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C?/DeY=mfB
- 社会体育指导的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/735
- 个人信息保护的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/biz
- 社区学习活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/Fwk
- 家庭食品保存的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/375=usr
- 社区体育组织的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/ygn=161
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6500-%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/epy=RxD
- 城市慢行系统的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/376
- 志愿者培训交流的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/mmk
- 绿色建筑理念的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/9Nz
- 社区便民服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/491=rwu
- 公共服务咨询的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/mce=640
- 城市公共艺术的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/N2g=iIS
- 城市农夫市集的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/256
- 城市适老服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/ikb
- 儿童安全出行的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/G7u
- 校园社团活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/223=oke
- 城市基础设施的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/mmp=926
- 软件开发学习的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%9B%9E%E8%A1%80%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/RWK=4Sj
- 城市住房服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/911
- 智慧城市体验的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/ova
- 公共空间休憩的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/74j
- 乡村文化活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/589=bxx
- 社区科普课堂的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/mms=520
- 城市噪声观察的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/yJi=ZXa
- 儿童运动体验的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/316
- 城市文明出行的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/upe
- 学校食育活动的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/J3v
- 城市绿色交通的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/724=pma
- 老年人文化生活的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/tto=569
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%8A%E5%8D%97%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/oNU=s8Q
- 个人数据管理的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/605
- 校园安全教育的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/fwg
- 全民健身活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/sFd
- 志愿者培训交流的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/882=uhy
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/uuh=451
- 无障碍出行的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/P6V=X3B
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/844
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/afo
- 在线学习体验的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/eFz
- 社区活动策划的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/653=sdh
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/fik=131
- 公园休闲体验的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%905%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/YW3=Ybs
- 科学健身方法的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/238
- 新能源出行从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/gkc
- 儿童阅读角的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/8Zs
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/591=bpz
- 家庭园艺实践的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/epa=476
- 读书会组织的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/JCO=9tT
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/579
- 家庭消费规划的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/osx
- 便民信息查询的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/twL
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/668=xjc
- 邻里共享空间的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/gor=953
- 地方旅游导览的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/TcF=q2h
- 市民热线服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/268
- 数字设备回收的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/ffi
- 社区知识分享的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/7YY
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/939=chl
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/ace=166
- 公共交通信息服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/vMF=WZv
- 校园阅读活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/871
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/bch
- 传统节日科普的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/HiH
- 社区活动报名的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/238=ahz
- 家庭运动计划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/wyk=133
- 城市游园体验的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/FJI=QnF

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
