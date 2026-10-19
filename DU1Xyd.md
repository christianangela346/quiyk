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

- 校园安全教育的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/709
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/qtv
- 绿色出行服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/4CL
- 居家适老化改造的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/761=uqy
- 社区安全巡查的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/rkq=643
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_3d%E7%B2%BE%E5%87%86%E6%95%B0%E6%8D%AE%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/j0d=RbH
- 城市夜间照明的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/118
- 食品配送体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/cng
- 城市便民驿站的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/XUZ
- 青年志愿活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/093=iai
- 城市慢行系统的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/vot=652
- 安全出行教育的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VII%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/vk3=L5i
- 电子商务服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/166
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mup
- 小微企业服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/41t
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/313=diu
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/qbg=610
- 城市建设科普的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%87%E7%A5%9E3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/t2q=8tp
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/295
- 网络信息辨识的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/zbo
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/1KM
- 图书馆活动策划的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/187=xge
- 家庭急救准备的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/teu=547
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9ai%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/cnR=3Zc
- 公共交通接驳的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/221
- 线上办事服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hni
- 城市农夫市集的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Q3r
- 课后服务体验的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/154=pqx
- 健康饮水科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/myb=661
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A98vlII-%E5%BD%A98VIII_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ZEh=zBI
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/739
- 社区共享书架的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/bps
- 灵活就业交流的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/LGB
- 终身学习资源的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/627=eex
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/rsa=298
- 城市便民驿站的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/QZW=wQR
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/186
- 基层医疗预约的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/aes
- 社区快递服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/NGc
- 医院导诊服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/113=lfe
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/imp=283
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/X5Y=pkt
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/679
- 亲子科普活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/gdk
- 个人信息保护的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/wfP
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/292=lfm
- 社区志愿服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/hgu=009
- 本地旅行体验的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8vl_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/P1Y=3md
- 数字公共文化的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/930
- 乡村产业科普的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/fdo
- 青年职业探索的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/cZ1
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/045=fqv
- 基层健康服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/jbb=209
- 安全出行教育的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/8kH=FQk
- 家庭环保行动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/273
- 数字公共文化的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/hht
- 数字生活课堂的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/JhF
- 公共设施维护的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/327=qzu
- 小微企业服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/gph=779
- 城市建设科普的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Eiv%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/KbK=E2u
- 绿色生活实践的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/942
- 社区手工活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/bgy
- 市民热线服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/ZtB
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/083=cbn
- 公益活动组织的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/dcm=609
- 地方民俗记录的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5%E6%AD%A3%E5%BC%8F%E7%89%88_360%E7%9B%B4%E6%92%AD?/gXn=OVZ
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/975
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/udk
- 便民信息查询的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/8as
- 家庭节能实践的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/359=qof
- 家庭消费规划的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/ypy=871
- 文化讲座服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/hiz=lNU
- 城市夜间照明的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/712
- 城乡交流活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/rbr
- 公园无障碍服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/M8R
- 本地旅行体验的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/462=plr
- 文化讲座服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/evg=261
- 科技馆参观体验的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/dpE=Cp3
- 家庭用电安全的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/660
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/rsi
- 乡村文化活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/xRM
- 租房信息服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/219=ozw
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/tcv=840
- 健康信息获取的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/9Sp=pwz
- 本地消费场景的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/633
- 学校体育活动的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/nxm
- 人工智能科普的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/5Jc
- 食品安全科普的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/196=wvq
- 无障碍信息设计的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/rui=824
- 便民维修服务的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/QdH=N4W
- 数字艺术创作的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/741
- 儿童友好街区的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/mxm
- 城市博物馆服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/S9W
- 社区活动策划的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/532=rjf
- 乡村生态观察的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/kds=592
- 就业技能培训的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/6U4=sq8
- 地方文化传播的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/221
- 就业技能培训的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/urb
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/ilS
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/115=tul
- 通勤路线规划的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/xds=087
- 城市树木认养的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8F%91%E5%A4%A7%E8%B4%A2%E5%BD%A9%E7%A5%A8%E5%B0%81%E7%A5%9E%E7%A5%A8%E6%88%BF_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/fbj=CnM
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/331
- 城市基础设施的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/phh
- 城市文化路线的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/LgY
- 便民服务地图的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/039=cwe
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/ics=415
- 家庭急救准备的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/WmB=OsG
- 儿童安全出行的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/441
- 城市生活服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/sdh
- 小区停车协商的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/XFe
- 数字支付体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/822=wga
- 青少年科普实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/qej=225
- 社区公共卫生的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/rH6=NRY
- 市民意见收集的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/614
- 社区设施共享的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/try
- 城市骑行环境的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/tzv
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/796=guk
- 骑行路线规划的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/hyu=820
- 家庭健康管理的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/p7C=U2n
- 数字政务体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/558
- 城市社区治理的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/qwm
- 街道综合服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/jqd
- 小区电梯维护的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/982=uef
- 乡村公共阅读的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/tcd=023
- 家庭园艺实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/vaJ=niM
- 社区体育组织的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/959
- 便民服务窗口的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/hgj
- 本地消费场景的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/haZ
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/787=cbx
- 街头绿植养护的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/cfv=248
- 智慧停车服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/GFh=cnj
- 校园社团活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/424
- 城乡公共服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/vbg
- 节日文化体验的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/Vk2
- 儿童户外活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/303=qof
- 社区家政服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/wla=367
- 校园社团活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/28o=aYQ
- 环境教育课程的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/927
- 公共设施维护的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/pcq
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/9tJ
- 城市公共座椅的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/131=qwc
- 软件开发学习的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/yrb=931
- 社区环保活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/Rx5=tw4
- 公共交通接驳的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/435
- 远程协作工具的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/nsa
- 地方民俗记录的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/ClG
- 职业技能学习的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/192=uan
- 农贸市场环境的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/zuo=788
- 科普展览体验的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/DPD=6Sx
- 儿童安全出行中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/572
- 乡村产业科普的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/nnp
- 食品配送体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/TI1
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/007=dqa
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/cqh=115
- 公共健身器材的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/Bix=PVk
- 公交站点体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/897
- 公共服务咨询的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/aps
- 儿童安全出行的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/9YD
- 本地旅行体验的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/510=hrc
- 创业经验分享的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/slc=192
- 城市住房服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/CK8=rWX
- 校园社团活动的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/819
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/myl
- 社会体育指导的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/ssr
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/960=zun
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/pnu=381
- 全民健身活动的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/7It=jhP
- 城市步行友好的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/043
- 科学教育活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/wvi
- 本地消费场景的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/YCH
- 城市应急广播的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/454=gle
- 绿色快递包装的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/ihx=494
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/V9E=7bn
- 家庭防灾准备的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/657
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/mwv
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/Gqr
- 健康饮水科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/227=bty
- 老年数字阅读的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/vjb=878
- 城市地名文化的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/sq9=ldr
- 应急物资管理的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/741
- 物业服务沟通的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/hzd
- 文明养宠科普的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/kSX
- 城市游园体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/328=gyt
- 智慧城市体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/llk=158
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/c6y=Rr0
- 家庭运动计划的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/102
- 安全出行教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/pyp
- 城市文化路线的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/EQS
- 农贸市场环境的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/613=qhb
- 城市共享单车的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/feq=735
- 绿色校园实践的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/yXe=hkr
- 家庭用电安全的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/539
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/xmr
- 旧物循环利用的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/I3H
- 全民健身活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/996=koe
- 城市建设科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/bzc=650
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/C3H=Ffv
- 社区便利生活的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/317
- 城市人文观察的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/rsm
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/5h9
- 低碳社区实践的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/989=kss
- 老年智能设备的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/ora=609
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/NUv=SCI
- 运动安全知识的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/091
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/lcz
- 环境监测科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/px5
- 基层健康服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/228=zmh
- 新能源知识普及的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/ghv=260
- 环境监测科普的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/LhX=wt8
- 数字学习资源的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/889
- 绿色快递包装中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/qzx
- 数字档案服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/k6H
- 开放式学习空间的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/484=nrg
- 科学观察活动中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/asq=747
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/rrS=HRt
- 公共服务沟通的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/259
- 便民服务地图的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/nvi
- 社区修缮行动的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/tPL
- 医院导诊服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/557=mxs
- 社区体育组织的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/duv=469
- 社区运动空间中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/Ll1=3N5
- 便民维修服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/008
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/osv
- 小区公共照明的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/lK5
- 青少年科技社团的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/760=lhh
- 街区更新实践的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/wmg=081
- 公共场馆服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/2bg=Cdk
- 家庭消费规划的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/641
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/sqo
- 科学健身方法的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/Ejj
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/641=tct
- 乡村生态观察的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/sqq=373
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/lJf=KD7
- 城市公共标识的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/761
- 健康饮食教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/swn
- 校园阅读活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/HZN
- 儿童户外活动的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/615=jtf
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/reu=578
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/br3=vfc
- 公共空间导览中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/744
- 乡村教育资源的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/dkm
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/65P
- 读书会组织的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/210=uha
- 数字便民地图的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/yme=398
- 校园节能行动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/e3s=6VO
- 社区心理支持的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_360%E5%9B%AD%E8%89%BA?/849
- 街区小店体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_360%E5%9B%AD%E8%89%BA?/lrt
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_360%E5%9B%AD%E8%89%BA?/jFN
- 儿童安全出行的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_360%E5%9B%AD%E8%89%BA?/262=qgg

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
