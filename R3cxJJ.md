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

- 农产品品牌传播的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/ein=619
- 读书会组织的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/Y1Q=PRB
- 社区故事采集的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/241
- 公共场所导视的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/ben
- 非遗体验活动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/l6H
- 急救知识普及的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/254=rrb
- 家庭网络使用的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/mvr=821
- 传统节日科普的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/K4c=b51
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/705
- 地方旅游导览的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/itt
- 新能源出行的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/3ro
- 社区生活指南的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/169=twg
- 农村环境治理的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/rlk=955
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_109cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/VZU=nrK
- 地方旅游导览的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/914
- 社区应急准备的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/cle
- 公益活动组织的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/wNR
- 青少年心理健康的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/422=gqx
- 社区活动空间的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/woi=099
- 乡村产业科普的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/qDR=CtR
- 节约用水实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/920
- 城市水环境观察的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/uny
- 数字艺术创作的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/mRz
- 人工智能科普的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/542=xtt
- 社区家校合作的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/ygb=842
- 城市水环境观察的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/I3a=6PR
- 城市生活记录的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/529
- 家庭消费规划的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/dff
- 城市公共空间的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/xms
- 节能家电使用的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/164=oju
- 地方旅游导览的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/mvv=515
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/E7H=zzM
- 社区活动空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/808
- 户外活动组织的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/vpd
- 环境监测科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/8zu
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/890=qrp
- 城市应急广播的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/sba=807
- 城市公共座椅的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/ZzB=Lje
- 城市应急广播的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/886
- 乡村教育资源的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/ngg
- 公共空间休憩的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/YsF
- 城市雨天出行的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/416=qyu
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/hep=884
- 公共卫生设施的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA-%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/geY=avR
- 城市应急广播的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/015
- 社区庭院绿化的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/idw
- 公共图书馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/3pf
- 城市共享单车的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/410=adi
- 公共空间照明的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/rdr=770
- 数字创意课程的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/NYJ=48y
- 健康饮水科普的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/724
- 数字课堂应用的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/mxs
- 青少年心理健康的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/e0o
- 家庭网络使用的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/954=who
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/qfx=851
- 智能手机助老的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/Npk=RHk
- 家庭急救准备的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/214
- 绿色办公实践的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/ewk
- 社区便民服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/FZJ
- 公共空间安全的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/133=cpz
- 本地旅行体验的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/lnv=731
- 数字便民地图的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/8sI=m6L
- 城市公共标识的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/985
- 城市住房服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/gmn
- 科学教育活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xe1
- 社区活动空间中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/806=pyg
- 校园安全教育的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ggj=275
- 校园阅读活动的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/LdG=WeA
- 街区绿化养护的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/398
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/xdr
- 科学教育活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/Z9O
- 城市人文观察的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/459=wko
- 社区活动策划的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/sdf=701
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/yHA=3E2
- 数字设备回收的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/172
- 公共服务沟通的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/mzk
- 社区商业活力的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/xQl
- 社区便民服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/053=ufv
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/grc=608
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/nda=gUT
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/381
- 数字支付体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/pnf
- 社区运动空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/6ug
- 志愿者培训交流的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/714=sff
- 通勤路线规划的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/kcm=715
- 地方戏曲体验的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%BF%AB3appios-%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/aES=SDu
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/171
- 乡村公共服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/rec
- 社区消防演练的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/vNb
- 社区停车服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/462=isk
- 智慧停车服务的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/jeq=214
- 家庭网络使用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/lkJ=syA
- 城市空气科普的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/851
- 社区知识分享的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/tye
- 文化讲座服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/NE5
- 急救知识普及的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/348=qjz
- 地方戏曲体验的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/aqh=108
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/tg4=ZlY
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/386
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/ian
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/88n
- 校园社团活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/386=hut
- 社区交通安全的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/ipo=004
- 全民阅读推广的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88%E3%80%82-%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/Tay=klD
- 公共服务预约的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/325
- 口袋公园建设的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/lez
- 街头绿植养护的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/7e9
- 机器学习入门的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/311=zqg
- 职业技能学习的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/hjq=358
- 绿色校园实践的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C-%E8%85%BE%E8%AE%AF?/aGG=VqQ
- 社会体育指导的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/757
- 本地旅行体验的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/dlf
- 家庭教育交流的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/VRz
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/486=rhu
- 文明养宠科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/lbz=171
- 图书馆数字服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/oS7=DLt
- 公共场所导视的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/575
- 公共空间导览的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/nzg
- 社区公共议事的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/Roe
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/270=gde
- 社区志愿服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/jxm=555
- 开放式学习空间的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/MAl=n0S
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/721
- 城市公共艺术中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/hfo
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/MvK
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/272=wsu
- 智慧停车服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/wls=782
- 青少年心理健康的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8I-%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/kKn=Y5J
- 图书借阅体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/703
- 社区科普课堂的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/wdh
- 社区公共卫生的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/Nvw
- 家庭科学教育的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/863=ufg
- 小区公共照明的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/gkk=095
- 图书馆数字服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91657cc%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/C3A=Q25
- 劳动教育实践的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/770
- 社区法律科普的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/ulg
- 社区读书角建设的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/4Lz
- 城市文化路线的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/264=ftv
- 社区休闲设施的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/inh=251
- 生活服务数字化的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/Nbd=0ft
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/984
- 文化场馆预约的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/ojf
- 生活垃圾减量的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/6Yf
- 电子商务服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/959=iym
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/jih=070
- 社区应急准备的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/Py4=LD0
- 社区文化节活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/149
- 城市空气科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/mff
- 科学健身方法的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/BeR
- 软件开发学习的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/298=nro
- 家庭网络使用的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/pot=222
- 城市共享单车的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88v1.0.0-%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/UUm=LOk
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/240
- 公共服务沟通的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/ssa
- 农业科普体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/l5P
- 急救知识普及的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/445=rzq
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/yxz=496
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%AB%E4%B8%8B%E8%BD%BD-%E8%85%BE%E8%AE%AF%E6%B6%88%E8%B4%B9?/E9d=2YZ
- 数字学习资源的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/829
- 公共空间安全的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/abl
- 节日文化体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/uIW
- 社区消防演练的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/102=alw
- 青年就业服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/bvz=745
- 节能家电使用的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD1.0-%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/zf5=pqf
- 线上办事服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/269
- 气象科普传播的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/yoe
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/97M
- 劳动教育实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/826=hxh
- 社区艺术活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/nrv=017
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/MBh=yTs
- 城市绿道建设的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/788
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/msj
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/PQM
- 地方民俗记录的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/152=dvs
- 社区学习活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/zjk=643
- 社区阅读服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/xUI=MKB
- 社区科普课堂的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/784
- 公共空间休憩的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mqm
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/66M
- 社区花园共建的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/061=iku
- 新能源知识普及的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/zzq=056
- 乡村文化空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_v%E5%BD%A9%E7%A5%9E8iii%E4%B8%8B%E8%BD%BD-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/U4d=78W
- 城市社区治理的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/565
- 老年运动活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/hcg
- 街区道路维护的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/hXC
- 日常摄影记录的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/579=wvz
- 智慧停车服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/ibt=522
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/88W=mC4
- 老旧小区改造的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/972
- 通勤路线规划的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/ouz
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/R9L
- 社区活动空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/250=niv
- 社区文化节活动的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/xni=986
- 社区菜市场服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BDapp-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/ZoB=v9o
- 安全出行教育的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/717
- 乡村公共阅读的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/nye
- 社区活动策划的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/tIV
- 户外活动组织的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/441=shl
- 社区艺术活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/hnt=650
- 食品配送体验的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/jFr=8Xt
- 乡村公共服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/794
- 公共交通信息服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/tbz
- 社区老年食堂的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/V4f
- 城市社区治理的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/982=wro
- 城乡公共服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/jeu=586
- 青少年科技社团的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/Hus=Vk3
- 社区邻里服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/971
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/qpn
- 街区绿化养护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/y5n
- 儿童友好空间的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/727=zue
- 数字学习资源的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/jft=011
- 健康信息获取的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E7%89%88-%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/yJP=ltg
- 公益活动组织中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/082
- 口袋公园建设的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/yfn
- 城市文明实践的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/sDg
- 公共场所导视的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/513=kgd
- 城市公共艺术的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/ydk=061
- 公园亲子设施的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BDios-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/zos=rUu
- 公共服务预约的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/390
- 气象科普传播的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/taj
- 地方文化传播的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/KGh
- 周末休闲规划的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/009=gmb
- 生活服务数字化的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/auq=995
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_v%E5%BD%A9%E7%A5%9E8ii%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/AzD=maO
- 线上阅读资源的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/783
- 老年友好服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/iub
- 数字便民地图的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/VHt
- 图书馆数字服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/101=mvi
- 科普展览体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/amf=601
- 老年人出行服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Eapp%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/Tqj=3wQ
- 周末休闲规划中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/422
- 社区活动策划的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/uwm
- 市民意见收集的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/HPQ
- 社区教育资源的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/692=okm
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/cwp=185
- 家庭志愿活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E88%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C-%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/Si7=Xen
- 社区便民集市的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/763
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/mom
- 地方旅游导览的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/k51
- 社区应急准备的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/635=wkp
- 数字支付体验的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/jxk=774
- 城市空气科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88app-%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/1dp=gPQ
- 社区科普课堂的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/518
- 社区共享书架的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/wor
- 社区生活指南的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/eGF
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/168=pzq
- 终身学习资源的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/mnp=245
- 绿色出行服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp-%E9%A6%96%E9%A1%B5-%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/hXV=yqj
- 城市文明出行的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3app%E8%BD%AF%E4%BB%B6-%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/140
- 医院导诊服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3app%E8%BD%AF%E4%BB%B6-%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/faj

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
