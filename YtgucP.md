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

- 家庭饮食安排的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/955
- 城市体育设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/myu
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/4zR
- 家庭健康科普的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/437=azu
- 社区家校合作的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/okd=916
- 物业服务沟通的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E4%B8%93%E9%A2%98?/Kxv=bjb
- 便民服务窗口的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/848
- 本地消费场景的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/imx
- 公共空间导览的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/Ncp
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/004=wsd
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/tmd=807
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/H7g=2dP
- 城市适老服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/026
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/ooy
- 智慧城市体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/iOR
- 社区健康讲座的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/827=iyv
- 城市夜间生活的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/yed=400
- 便民服务地图的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/Wtg=LyZ
- 家庭科学教育的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/856
- 生活技能分享的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/lga
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/kDm
- 数字地图应用的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/159=sky
- 亲子科普活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/rfb=961
- 社区教育资源的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/fdb=CkE
- 老年数字阅读的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/866
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/iye
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/ezu
- 家庭健康科普的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/260=hth
- 数字设备回收的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/cyl=460
- 安全出行教育的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/CMN=zVX
- 城市雨天出行的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/096
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/cki
- 学校食育活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/IrD
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/565=ejh
- 安全出行教育的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/rxu=433
- 文化场馆预约的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/zT9=jmt
- 乡村公共文化的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/467
- 公共空间照明的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/yib
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/XdZ
- 城市夜间照明的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/133=vhw
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/adp=493
- 健康步道使用的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/WKa=t6g
- 家庭防灾准备的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/462
- 社区信息发布的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/amb
- 本地历史资料的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/DqP
- 老年数字阅读的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/167=egt
- 低碳社区实践的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/usw=923
- 社区手工活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/PJ3=TFG
- 公共服务预约的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/881
- 数字阅读服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/hno
- 乡村公共阅读的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/sJX
- 课后服务体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/359=dlt
- 家庭环保习惯的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/uta=784
- 社区心理支持的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%9F%A5%E7%9C%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/mg0=pVF
- 学校食育活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/454
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/cka
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/N8U
- 终身学习资源的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/236=xpd
- 城市社区治理的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/anv=462
- 应急物资管理的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/Yp9=Zz0
- 绿色快递包装的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/400
- 软件开发学习的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/rqb
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/hu5
- 社区养老服务的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/319=jmq
- 机器人科普活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/nyw=376
- 城市共享单车的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/kjk=p4U
- 城市应急科普的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/142
- 公共服务评价的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/dnv
- 社区文化节活动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/2qu
- 乡村产业科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/683=ump
- 社区心理支持的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/ggf=260
- 公共场所导视的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/76d=YjQ
- 家庭运动计划的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/675
- 市民热线服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/uda
- 老年数字阅读的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/EYs
- 家庭节能实践的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/473=xci
- 公共场所导视的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/umv=898
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/NQB=49U
- 灵活就业交流的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/515
- 公共场馆服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/tbt
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/3VR
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/869=tlz
- 数字政务体验的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/urc=665
- 家庭节能实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/25V=xgK
- 老年人文化生活的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/460
- 科学信息获取的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/iir
- 城市公共艺术的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/dax
- 社区便民服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/083=ydw
- 社区应急准备的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/ief=964
- 基层健康服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/u6I=OJp
- 老年人文化生活的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/333
- 科普展览体验的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/dbq
- 市民意见收集的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/a4b
- 环境监测科普的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/133=oyd
- 家庭饮食安排的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/vkd=300
- 通勤路线规划的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/fFi=j1d
- 社区信息发布中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/116
- 数字公共文化的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/lml
- 家庭饮食安排的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/jHS
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/799=hyp
- 公共文化活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/utu=161
- 城市运动公园的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/uWt=2PI
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/061
- 家庭阅读计划的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/ebf
- 社区科普课堂的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/FKN
- 户外活动组织的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/883=ybi
- 基层医疗预约的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/ulx=740
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/eSS=vjw
- 数字创意课程中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/371
- 城乡交流活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/ida
- 社区宠物管理的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/Edq
- 城市基础设施的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/692=iek
- 街头绿植养护的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/rqr=321
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E6%91%98?/miE=okV
- 家庭养老规划的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/385
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/rej
- 数字阅读服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/9EV
- 社区志愿服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/545=gdv
- 图书借阅体验的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/wdy=763
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/aW6=zmw
- 社区宠物管理的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/746
- 节日文化体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/lis
- 旧物循环利用的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/N9h
- 社区运动空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/156=xmg
- 农贸市场环境的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/kug=299
- 社区休闲设施的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/i2c=9vV
- 社区宠物管理的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/072
- 小区公共照明的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/hdf
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/jO1
- 城市应急科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/178=eah
- 智慧城市体验的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/uvb=258
- 职业技能学习的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/laR=sj9
- 科普展览体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/655
- 社区休闲设施中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/aku
- 无障碍信息设计的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/ZCe
- 地方文化传播的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/187=evb
- 数字资源检索的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/roc=903
- 乡村公共阅读的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%97%B6%E8%AF%84?/xf1=dAT
- 数字支付体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/822
- 急救知识普及的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/gvd
- 社区健康讲座的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/J6I
- 社区养老服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/601=wjl
- 节能家电使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/mfb=187
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/7hv=Xf5
- 社区应急准备的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/136
- 城市体育设施的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/vbj
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/089
- 公共设施使用的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/336=ohg
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/jsn=139
- 公共服务沟通的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/UUs=U5q
- 社区互助网络的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/273
- 城乡交通衔接的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/wss
- 儿童友好空间的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/RrL
- 社区协商议事的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/515=xes
- 志愿服务平台的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/gtm=355
- 口袋公园建设的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/Vts=x0l
- 食品配送体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/188
- 网络信息辨识的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/ngl
- 线上办事服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/L3O
- 休闲运动入门的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/269=oxu
- 地方民俗记录的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/ums=228
- 街头绿植养护的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/Jez=Tz3
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/584
- 老年人日常照护的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/iil
- 城市噪声观察的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/BIc
- 个人时间管理的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/467=myc
- 骑行路线规划的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/lim=898
- 社区修缮行动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/VQ4=YCC
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/135
- 城市夜间照明中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/nqz
- 家庭运动计划的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/B5A
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/409=xza
- 城市地名文化的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/rom=083
- 社区活动策划的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E5%8E%BF%E5%9F%9F?/2YQ=1Lw
- 租房信息服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/236
- 小区停车协商的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/bav
- 社区老年食堂的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/Jnc
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/119=bjj
- 社区修缮行动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/gtr=734
- 家庭健康管理的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/KBu=pZq
- 图书借阅体验的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/645
- 城市运动公园的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/bmb
- 儿童阅读角的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/SHE
- 绿色快递包装的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/350=fmt
- 小微企业服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/zwn=738
- 老年人文化生活的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/HTf=Rmw
- 传统节日科普的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/884
- 基层服务创新的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/nqo
- 社区托育服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/HJ5
- 图书馆活动策划的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/860=nqx
- 数字艺术创作的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/slj=823
- 社区垃圾分类的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/mfW=dXX
- 环境教育课程的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/535
- 农业科普体验的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/paw
- 城市生活服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/5vv
- 乡村阅读空间的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/456=xxc
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/tre=267
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/Wgz=pXf
- 家庭消费规划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/474
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/zih
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/VTu
- 公园无障碍服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/490=dya
- 急救知识普及的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/mra=991
- 电动汽车充电的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/pTs=7V0
- 地方旅游导览的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/320
- 乡村公共服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/bei
- 公园休闲体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/iV1
- 青少年户外教育的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/890=mbe
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/zqb=800
- 城市夜间照明的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_36%E6%B0%AA%E4%BD%93%E8%82%B2?/XN3=qkw
- 城乡公共服务的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/387
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/ldt
- 公共服务数字化的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/97s
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/721=nfa
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/wtl=498
- 健康饮水科普的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/0np=o8B
- 社区阅读服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/024
- 租房信息服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/fdm
- 街区更新实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/VZb
- 社区故事采集的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/092=pki
- 社区商业活力的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/dbg=035
- 家庭防灾准备的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/Dze=EuK
- 社区公共议事的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/441
- 图书借阅体验的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/ydr
- 地方旅游导览的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/9iS
- 城市建设科普的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/523=aks
- 城市公共空间的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/zxy=101
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/W4a=6NF
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/097
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/ksc
- 社区安全巡查的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/Qvo
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/613=qcw
- 家庭运动计划的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/qep=508
- 绿色快递包装的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/6BE=395
- 社区停车服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/805
- 环境教育课程的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/hft
- 公共空间导览的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/3ot
- 公共服务评价的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/989=ubk
- 在线学习体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/gco=384
- 社区交通安全的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/cYy=HmU
- 绿色出行服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/623
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/tpn
- 学校食育活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/HnI
- 城乡交流活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/964=jyj
- 科学信息获取的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/vhg=028
- 灵活就业交流的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/DMa=Qjf
- 城市休闲步道的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/039
- 远程协作工具的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/kzo
- 社区儿童活动中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/EOo
- 社区花园共建的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/620=jnv

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
