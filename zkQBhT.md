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

- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/vyl=869
- 城市社区治理的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/eDK=DVn
- 社区志愿服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/048
- 老年人文化生活的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/sad
- 社区故事采集的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/75Q
- 数据分析入门的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/964=bgx
- 垃圾分类指导的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/dcl=198
- 街区绿化养护的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E5%99%A8_%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/zRi=Bjv
- 健康信息获取的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/041
- 城市地名文化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/nvo
- 公共空间照明的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/Wxs
- 城市公共艺术的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/820=kzt
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/mhz=397
- 城市社区治理的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/R4U=6v5
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/440
- 城市游园体验的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/whw
- 家庭理财科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/Q5k
- 邻里互助活动的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/013=uji
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/oco=179
- 绿色消费选择的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/PAR=Yen
- 城市应急科普的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/962
- 家庭科学教育的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/aid
- 个人数据管理的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/rJD
- 城市人文观察的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/205=bmx
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/myi=054
- 生活服务数字化的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/n9n=ldL
- 乡村公共文化的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/514
- 社区科普课堂的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/vmm
- 社区手工活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/wgW
- 软件开发学习的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/607=asz
- 骑行路线规划的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/mrt=357
- 健康饮水科普的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/ZlD=R3W
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/298
- 青年志愿活动的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/dlk
- 节能家电使用中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/9LY
- 生活垃圾减量的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/626=kop
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/vhg=806
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/ruv=Cw6
- 非遗体验活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/718
- 公共服务沟通的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/xgt
- 城市树木认养的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/2q4
- 社区托育服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/363=fad
- 社区休闲设施的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/xyr=994
- 地方美食文化的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%97%B6%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/DE6=hXu
- 节日文化体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/172
- 公共服务评价的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/mek
- 校园节能行动的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/p1r
- 机器人科普活动中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/234=iut
- 数字设备回收的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/tpv=019
- 乡村文化活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/oYr=Fie
- 社区手工活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/394
- 社区互助网络的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/wfv
- 乡村电商实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/YWW
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/242=hpf
- 周末休闲规划的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/lty=381
- 公共健身器材的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/mDT=juv
- 社区商业活力的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/637
- 乡村教育资源的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/yqe
- 数字素养提升的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/AC1
- 数字设备回收的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/829=efo
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/wuh=594
- 社区知识分享的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/XMm=Zhs
- 乡村生态观察的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/356
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/seo
- 在线学习体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/zm1
- 公共设施维护的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/426=mol
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/yfi=458
- 地方美食文化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/Dkf=z6D
- 城市应急广播的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/471
- 城市基础设施的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/ghn
- 课后服务体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/0Ze
- 城市基础设施的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/115=qav
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/sha=668
- 社区商业活力的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/SgF=IBi
- 安全出行教育的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/764
- 城市应急广播的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/drw
- 智能手机助老的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/AyN
- 家庭理财科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/249=ahg
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/iqs=621
- 开源技术交流的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/wDO=UYP
- 社区便利生活的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/958
- 软件开发学习的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/wbh
- 城市空气科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/1mh
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/760=zdl
- 环境教育课程的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/wls=655
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/sOh=1k9
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/876
- 气象科普传播的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/nhc
- 城市游园体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/Mr5
- 家庭用电安全的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/077=bwg
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/eux=750
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%99%BE%E7%A7%91?/044=dRf
- 数字课堂应用的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/107
- 城市夜间照明的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/gsx
- 图书馆数字服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/Mtz
- 城市步行友好的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/962=iwk
- 儿童运动体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/xbz=070
- 户外活动组织的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/E9g=9Hf
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/567
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/tch
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/u1Z
- 安全出行教育的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/188=emr
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/ler=205
- 乡村产业科普的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/KkR=SXR
- 社区知识分享的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/360
- 个人时间管理的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/uit
- 数字地图应用的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/NL7
- 小区公共照明的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/822=cfm
- 数字创意课程的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cuc=788
- 信息无障碍体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E8%B5%9A_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Ggn=yD4
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/512
- 老年友好服务的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/ckz
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/WF2
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/142=hyd
- 软件开发学习的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/glg=280
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/lOV=Kmo
- 城市公共标识的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/273
- 机器人科普活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/hmd
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/ekV
- 绿色校园实践的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/049=asn
- 数字课堂应用的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/djj=019
- 节气饮食文化的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/74M=A19
- 社区应急准备的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/719
- 气象科普传播的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/lvh
- 地方文化传播的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/3yJ
- 社区公共餐饮的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/394=ghw
- 城市文明出行的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/prb=914
- 农贸市场环境的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/uqz=8fn
- 地方文化传播的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/974
- 节能家电使用的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/vhm
- 邻里共享空间的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/1dJ
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/609=agv
- 公共文化活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/jjb=668
- 小区公共照明的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%8A%82%E5%A5%8F%E5%A4%AA%E7%A8%B3%E5%AE%9A_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/wSi=WLD
- 开放式学习空间中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/469
- 软件开发学习的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/dfp
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/rbZ
- 社区活动策划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/303=wbi
- 地方文化传播的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/pnv=178
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E8%B4%A2%E7%A5%9E%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/yXP=VzD
- 城市社区治理的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/861
- 旧物循环利用的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/btk
- 绿色消费选择的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/lsI
- 旧物循环利用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/956=vlu
- 垃圾分类指导的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/jux=201
- 公共服务咨询的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%8E%92%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/OCy=Lok
- 城市博物馆活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/326
- 社区设施共享的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/zge
- 科学健身方法中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/fFn
- 公共空间休憩的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/115=pkp
- 公共场所导视的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/bku=818
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93D%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/Kpt=kc7
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/026
- 开放数据应用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/fgo
- 机器学习入门的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/TQB
- 老年人日常照护的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/580=aru
- 数字档案服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/wcp=819
- 城市水环境观察的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_300%E5%85%83%E5%80%8D%E6%8A%957%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/gTQ=WdI
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/861
- 城市树木认养的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/hnw
- 物业服务沟通的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/WR9
- 公共空间休憩的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/820=qvf
- 城市绿道建设的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/dyr=900
- 食品配送体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/zDT=PeL
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/134
- 信息无障碍体验的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/xuq
- 社区公共卫生的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/4LD
- 非遗体验活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/297=zwk
- 社区老年食堂的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/kvf=198
- 城市公共标识的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/Xa1=n1b
- 急救知识普及的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/424
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/dsh
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/5SX
- 急救知识普及的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/230=pta
- 城市水环境观察的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/jrl=066
- 健康饮水科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/jIc=kxx
- 城市社区治理的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/918
- 生活技能分享的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/qie
- 社区体育组织的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/HwE
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/435=khd
- 街区绿化养护的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/udd=727
- 公共服务预约的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/NNI=NVF
- 志愿者培训交流的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/010
- 社区托育服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/jwp
- 社区协商议事的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/eFu
- 社区安全巡查的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/418=nlr
- 青年志愿活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/hkv=503
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/0KI=61N
- 城市绿道建设的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/585
- 休闲运动入门的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/qfz
- 小区电梯维护的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/lJr
- 基层健康档案的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/998=hlg
- 家庭饮食安排的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/vvj=991
- 科学信息获取的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_300%E5%85%83%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%AF%A6%E7%BB%86%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/3m2=Pmo
- 健康信息获取的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/713
- 城乡公共服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/oih
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/15M
- 居民健康教育的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/955=wue
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/njo=105
- 全民阅读推广的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/QJx=v4V
- 志愿服务平台的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/253
- 社区老年食堂的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/zli
- 本地消费场景的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/COi
- 传统节日科普的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/150=bre
- 邻里共享空间的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/paw=516
- 农贸市场环境的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/HLi=2oa
- 农产品消费体验的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/595
- 文明养宠科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/hdj
- 老旧小区改造的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/XjY
- 家庭阅读计划的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/995=zvy
- 社区设施共享的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/cnv=243
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%91%98_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/uFC=3Uv
- 课后服务体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/415
- 机器人科普活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/rzx
- 家庭急救准备的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/auW
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/048=ipd
- 乡村公共文化的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/kfl=105
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/faF=zHs
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/983
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/vwf
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/XtN
- 公共服务指南的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/933=yjn
- 公交站点体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/nkf=656
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/ux5=sah
- 城市休闲步道的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/977
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/ppn
- 城市公共标识的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/1Rz
- 社会体育指导的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/003=lcl
- 城市公共艺术的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/poo=184
- 社区手工活动的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/sR5=Fos
- 本地消费场景的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/966
- 街区道路维护中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/ugx
- 城市公共厕所的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/b5o
- 城市体育设施的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/508=vty
- 便民信息查询的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/jig=628
- 社区法律科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/jBp=TeX
- 电动汽车充电的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/492
- 科学运动指导的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/kfd
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/4H0
- 物业服务沟通的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/618=ycc
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/ayv=771
- 城乡交流活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%92%8C%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/AXs=T6k
- 校园阅读活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/529
- 公共交通信息服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/nzd
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/8kg
- 生成式工具使用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/139=fup
- 农业科普体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/tyw=453
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/7lY=IGK
- 食品安全科普的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/251
- 环境监测科普的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/rok

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
