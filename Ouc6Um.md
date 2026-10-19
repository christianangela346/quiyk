# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 城市公共空间的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/825
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/rix
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/6aA
- 无障碍出行的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/593=jrb
- 无障碍出行的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/dwf=831
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%BE%A4%E6%8E%A8%E8%8D%90_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/BLZ=0gO
- 青年志愿活动的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/867
- 文明养宠科普的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/gxu
- 城市建设科普的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/6d1
- 城市展览体验中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/063=bxz
- 城市便民驿站的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/xwj=871
- 休闲运动入门的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_pk10%E4%BA%A4%E6%B5%81%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/9bu=AG4
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/518
- 社区科普课堂的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/bzs
- 社区知识分享的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/8ff
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/647=cjq
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/ztw=203
- 城市公共座椅的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81%E5%8C%BA_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/PBu=9lo
- 家庭用电安全的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/846
- 信息无障碍体验的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/ppg
- 城市文明出行的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/ZUX
- 智能家居应用的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/212=rit
- 社区邻里服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/feu=379
- 公共卫生宣传的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_pk10%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/9mr=ZbU
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/146
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/rsb
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/3NS
- 数字资源检索的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/879=ezq
- 老年数字阅读的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/dgz=697
- 社区宠物管理的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/swi=krN
- 社区家校合作的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/351
- 老年人出行服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/bwj
- 文明养宠科普的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/Xqm
- 个人数据管理的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/208=kzv
- 儿童友好空间的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/mri=859
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pk10%E7%89%9B%E4%BA%BA%E4%BA%A4%E6%B5%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/SuJ=oS7
- 城市共享单车的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/234
- 乡村生活观察的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/stg
- 儿童户外活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/OKO
- 公共服务预约的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/381=qeq
- 城市可持续生活的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/whd=485
- 家庭网络使用的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_pk10%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/9oD=jhr
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/559
- 城市应急广播的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/iqt
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/PdK
- 药品使用科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/081=cif
- 家庭理财科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/gmo=642
- 社区花园共建的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/DvY=2aN
- 城市适老服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/814
- 街区小店体验的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/hxg
- 城市建设科普的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/tTL
- 休闲运动入门的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/435=zox
- 社区法律科普的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/ndx=377
- 老年运动活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_pk10%E5%AF%B9%E5%88%B7%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/Ltt=Tr4
- 小区电梯维护的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/597
- 青少年科普实践的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/ogk
- 生成式工具使用中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/Gvc
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/471=pbr
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/ldo=092
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4--%EF%BC%88%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3%EF%BC%89_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/9bs=3AC
- 志愿者培训交流的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/912
- 社区知识分享的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/uie
- 城市运动公园的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/Y3U
- 城市文明实践的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/965=zmu
- 机器学习入门的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/lxg=030
- 青少年科普实践的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/F1R=5mV
- 亲子科普活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/505
- 文化场馆预约中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/cme
- 智慧停车服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/jWy
- 城市运动公园的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/416=uqp
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/dst=726
- 文化讲座服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/sHW=Nzx
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/799
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/naq
- 数字设备回收的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/rJm
- 便民服务窗口的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/620=xpj
- 街区绿化养护的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/txo=563
- 创业经验分享的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E8%B0%81%E6%9C%89%E8%8B%87_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/z3Y=WXy
- 非遗体验活动的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/782
- 青年志愿活动的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/idh
- 城市可持续生活的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/Jpl
- 家庭志愿活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/203=ggw
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/swh=333
- 社区学习活动的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/ATx=lCo
- 传统节日科普的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/706
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/hbr
- 社区防暑服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/4MB
- 数字学习资源的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/109=ccp
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/wdn=303
- 科学教育活动的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4%E5%8F%BC_36%E6%B0%AA%E5%88%8A%E7%99%BB?/yRl=O4h
- 城市绿色交通的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/297
- 街区小店体验的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/gsg
- 城市生活服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/CDy
- 老年友好服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/825=rue
- 城市休闲步道的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/waz=503
- 社区托育服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/duh=zT8
- 科学教育活动的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/187
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/thd
- 城市生活服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/wAr
- 社区教育资源的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/470=ldh
- 老年智能设备的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/qnd=155
- 数字设备回收的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/RMC=TpV
- 社区家政服务的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/888
- 老年人出行服务的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/tjt
- 社区垃圾分类的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/LUh
- 街区道路维护的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/459=agg
- 社区家政服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/lop=807
- 城市适老服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B8%B8%E6%88%8F%E7%BE%A4_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/uLz=05w
- 家庭食品保存的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/539
- 城市雨天出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/phh
- 全民阅读推广的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/t9o
- 青年志愿活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/503=dub
- 社区绿色空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/bfw=696
- 社区交通安全的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%89%BE%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/bCl=H8v
- 家庭理财科普的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/273
- 社区志愿服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/iud
- 社区防暑服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/26G
- 数字支付体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/335=msl
- 城市绿道建设的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/crp=039
- 公共健身器材的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/3wl=4nj
- 城乡公共服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/510
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/txk
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/8t8
- 乡村文化活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/501=ogc
- 社区家校合作的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/wlk=687
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4_360%E6%8A%95%E7%A5%A8?/sO4=qpa
- 科学信息获取的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/166
- 乡村电商实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/cvl
- 乡村生态观察的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/bma
- 旧物循环利用的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/400=ijy
- 本地消费场景的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/ziu=578
- 街头绿植养护的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/BhK=T4e
- 公共空间导览的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/675
- 地方美食文化的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/ubc
- 应急物资管理的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/nqR
- 数字创意课程中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/835=hat
- 社区共享书架的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/uyg=757
- 医院导诊服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4----1_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/WpQ=pyg
- 家庭阅读计划的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/388
- 城市休闲步道的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/kgq
- 读书会组织从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/oQy
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/210=xiw
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/ver=138
- 公共设施维护的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%B7%9E10%E7%BE%A4-----1_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/x4k=vEB
- 公益活动组织的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/487
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/uhr
- 公共空间导览的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/8QS
- 环境监测科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/864=rex
- 光伏知识科普的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/lqm=994
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/YnT=f5Q
- 社区慢性病防控的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/406
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/qoq
- 城市游园体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/xKL
- 社区儿童活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/322=qjx
- 气象科普传播的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/yfq=046
- 城市骑行环境的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E9%9F%B3%E4%B9%90?/AvR=Qbi
- 读书会组织的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/851
- 校园阅读活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/iyx
- 地方民俗记录的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/kKy
- 社区学习活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/608=hto
- 街区道路维护的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/qsu=692
- 城市空气科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/pe0=EIP
- 城市文明实践的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/037
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/lpv
- 信息无障碍体验的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/9wV
- 城市可持续生活的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/057=ssq
- 乡村阅读活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/klk=733
- 乡村文化空间的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/slS=GDy
- 科学运动指导的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/032
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/gju
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/Xfs
- 乡村公共文化中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/451=erm
- 社区垃圾分类的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/eri=506
- 乡村产业科普的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/r69=GXW
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/428
- 数字公共文化中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/uil
- 老旧小区改造的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/vhN
- 儿童友好空间的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/434=yts
- 社区商业活力的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/xyy=616
- 社区心理支持的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/OFI=KY5
- 公共设施使用中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/262
- 开放数据应用的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/haz
- 职业技能学习的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/TW2
- 社区教育资源的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/850=rjz
- 社区家政服务的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/eav=211
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/dEt=YdH
- 数字公共文化的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/926
- 社区家政服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/jdb
- 公共设施使用的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/Mya
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/393=nqp
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/wso=644
- 地方民俗记录中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/PW3=2pt
- 科普展览体验的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/336
- 健康步道使用的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/oyt
- 青少年编程学习的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/YTd
- 数字学习资源的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/671=qra
- 乡村教育资源的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/ooc=076
- 绿色出行服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_360%E6%97%A5%E6%8A%A5?/DHU=NE7
- 数字便民地图的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/102
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/dti
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/m2R
- 公共服务预约的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/861=lwx
- 小区停车协商的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/ign=432
- 社区托育服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/QMF=N9F
- 在线学习体验的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/427
- 校园阅读活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/zfr
- 旧物循环利用的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/xLE
- 社区手工活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/857=egc
- 乡村产业科普的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/ocp=983
- 智慧城市体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/8cr=46W
- 信息无障碍体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/786
- 家庭急救准备的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/asf
- 校园安全教育的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/hyR
- 校园社团活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/758=xfi
- 农业科普体验的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/eyv=277
- 机器人科普活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/j8E=def
- 开放式学习空间的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/081
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/ery
- 科学信息获取的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/peV
- 社区协商议事的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/375=feu
- 社区庭院绿化的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/muc=300
- 课后服务体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/CqW=IAT
- 城市夜间照明的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/124
- 农业科普体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/rkc
- 城市展览体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/iMR
- 小区公共照明的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/170=gsz
- 智能家居应用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/ayi=082
- 社区科普课堂的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_360%E6%9C%AD%E8%AE%B0?/ZGO=RAz
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/558
- 骑行路线规划的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/ttu
- 安全出行教育的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/6hJ
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/980=xxh
- 灵活就业交流的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/qxn=406
- 城市骑行环境的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/MIV=q2Y
- 城市微更新实践的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/333
- 数字阅读服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/tlf
- 社区庭院绿化的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/BZQ
- 城市体育设施的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/712=ncb
- 家庭健康管理的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/das=231
- 口袋公园建设的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/xgG=iiY
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/641
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/bfz
- 青少年户外教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/Ak4
- 安全出行教育的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/301=eyj
- 地方旅游导览的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/bht=115
- 节能生活方式的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/4Vc=wUd
- 城市体育设施的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/914
- 物业服务沟通的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/feh
- 租房信息服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/A3Y
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/647=sfp

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
