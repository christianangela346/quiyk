# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 青少年科普实践的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%B9%BF%E8%A5%BF%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/VY1
- 街区道路维护的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%B9%BF%E8%A5%BF%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/030=jnd
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%B9%BF%E8%A5%BF%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/cci=446
- 街道综合服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%B9%BF%E8%A5%BF%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/ZhA=Htx
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/968
- 光伏知识科普的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/lzj
- 社区共享书架的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/wft
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/501=npi
- 家庭环保习惯的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/jiq=766
- 网络信息辨识的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/VSr=Geu
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/068
- 社区宠物管理的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/bnp
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/WSo
- 社区读书角建设的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/120=lwo
- 家庭理财科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/ksp=155
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%89%E5%BE%BD%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/tuA=VKD
- 青年就业服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/378
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/oer
- 非遗课堂体验的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/U5B
- 社区休闲设施的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/285=xtz
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/pem=968
- 公共卫生宣传的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%8A%E6%B5%B7%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/OBc=6Eu
- 乡村公共文化的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/622
- 数字创作工具的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/thk
- 社区信息发布的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/PkE
- 数字支付体验的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/564=lyr
- 智能家居应用的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/nei=374
- 消防知识宣传的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/YXg=aQ6
- 公交站点体验的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/641
- 无障碍信息设计的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/hsh
- 无障碍信息设计的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/yiY
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/638=gye
- 软件开发学习的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/syo=644
- 绿色校园实践的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/q0f=oh1
- 城市建设科普的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/349
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/jii
- 农业科普体验的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/pAE
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/405=wfn
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/wjm=870
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/NPx=sNa
- 节约用水实践的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/810
- 地方文化传播的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/aur
- 运动安全知识的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/lw0
- 社区家政服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/835=fux
- 数字地图应用的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/cus=216
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E6%A1%A3%E6%A1%88?/Umz=VVU
- 光伏知识科普的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/787
- 儿童户外活动的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/qon
- 市民热线服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/Npk
- 智慧城市体验的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/621=nyc
- 城乡交流活动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/jvq=700
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/yJO=atE
- 社区环保活动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/612
- 急救知识普及的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/ebm
- 机器人科普活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/gXj
- 公共空间休憩的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/887=tcv
- 社区活动空间的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/bhs=834
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94?/DpZ=9sK
- 个人数据管理的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/492
- 应急物资管理的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/ywm
- 社区活动空间的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/boq
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/551=sho
- 图书借阅体验的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/imw=088
- 校园节能行动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/pfR=FVS
- 公共服务指南的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/300
- 便民维修服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/rwu
- 环境监测科普的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/qdp
- 节气饮食文化的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/205=rfl
- 亲子阅读活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/bcc=676
- 本地消费场景的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9C%80%E6%96%B0%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E6%9C%9F%E8%B4%A7?/xGW=ZE2
- 老年数字阅读的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/179
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/ehn
- 骑行路线规划的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/347
- 社区协商议事的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/078=tln
- 城市微更新实践的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/axp=767
- 社区教育资源的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/EXQ=ads
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/231
- 家庭安全提示的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/tzv
- 小区电梯维护的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/UKD
- 绿色生活实践的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/009=iaz
- 租房信息服务的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/tub=988
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/pKD=elv
- 社区文化节活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/339
- 公共文化活动的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/qyu
- 社区便利生活中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/yfK
- 在线教育体验的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/961=dli
- 便民服务地图的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/tmj=082
- 社区手工活动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%AB%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/mnu=IRB
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/978
- 城市建设科普的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/als
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/BLu
- 亲子阅读活动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/010=wrn
- 城市生活服务的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/pnv=992
- 家庭急救准备的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/X2j=W6j
- 日常摄影记录的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/385
- 科学健身方法的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/wfk
- 便民服务地图的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/wEn
- 农贸市场环境中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/598=xad
- 气象科普传播的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/xvi=505
- 智能手机助老的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/A6S=bgE
- 农业科普体验的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/505
- 城市农夫市集的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/xnc
- 绿色校园实践的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/8OH
- 社区垃圾分类的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/677=nvv
- 乡村文化空间的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/vfa=132
- 环境教育课程的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/EbR=822
- 急救知识普及的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/904
- 图书借阅体验的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fzn
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/BY8
- 城市运动公园的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/534=dam
- 生成式工具使用的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gzs=296
- 城市公共空间的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/42u=Dot
- 通勤路线规划的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/723
- 基层服务创新的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/tem
- 公交站点体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/KxX
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/647=aro
- 公共空间安全的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/jxi=822
- 城市应急科普的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA?/y85=zz4
- 城乡交流活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/069
- 老年人日常照护的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/xyv
- 节约用水实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/K0N
- 文明养宠科普的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/524=mac
- 城市公共标识的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/yev=790
- 低碳社区实践中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/h4V=ZCl
- 家庭急救准备的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/571
- 休闲运动入门的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/nbj
- 生成式工具使用的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/Yg4
- 食品安全科普的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/440=spt
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/aot=970
- 社区公共议事的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/bCK=zfE
- 便民信息查询的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/028
- 社区商业活力的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/qcf
- 家庭消费规划的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/0a4
- 农产品消费体验的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/935=mfy
- 节日文化体验的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/beq=616
- 绿色出行服务的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/NwV=aKM
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/477
- 城市步行友好中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/irc
- 小微企业服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/5XK
- 网络安全教育的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/624=ypn
- 社区学习活动的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/woe=918
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/uQQ=X9r
- 城乡公共服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/944
- 科学信息获取的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/lfd
- 乡村产业科普的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/xyD
- 城市文明出行的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/583=dgz
- 公共空间导览的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/bmd=944
- 城市地名文化的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/3uf=ftD
- 城市运动公园的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/086
- 图书借阅体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/yjs
- 城市微更新实践的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/5Fe
- 社区互助网络的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/445=mjf
- 城市公共饮水的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/kuz=915
- 城市游园体验的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/7Rc=7j6
- 图书借阅体验的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/381
- 社区互助网络的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/sqf
- 城市文化路线的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/53e
- 乡村阅读活动的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/281=qqq
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/amm=878
- 公园亲子设施的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/stj=Ylk
- 农业科普体验的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/158
- 电子商务服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/ctl
- 儿童运动体验的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/nZy
- 户外活动组织的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/843=jrw
- 健康步道使用的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/sdy=904
- 公园亲子设施中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1-%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/dgd=uGJ
- 城市展览体验的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/519
- 邻里共享空间的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/oxj
- 市民热线服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/LA4
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/731=azb
- 乡村阅读活动的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/ynx=941
- 公共设施使用的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/jYc=wXP
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/357
- 节日文化体验的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/nbu
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/HL0
- 环境监测科普的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/827=sng
- 街头绿植养护的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/cka=382
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80-36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/Ypz=uoX
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/318
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/lnq
- 青年职业探索的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/zSa
- 家庭健康管理的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/396=jlu
- 社区老年食堂的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/wez=148
- 乡村产业科普的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/0pg=aLZ
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/238
- 老年智能设备的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/lkc
- 小区电梯维护的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/wah
- 数字资源检索的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/734=eye
- 社区快递服务中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/bgk=712
- 生活服务数字化的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/7jM=qgF
- 家庭消费规划的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/086
- 城市绿色交通的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/pvt
- 基层健康档案的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/MkS
- 城市便民驿站的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/005=kjx
- 城市共享单车的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/dna=985
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/giC=3wD
- 校园社团活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/018
- 公共图书馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/dew
- 家庭照护支持的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/n4v
- 居民健康教育的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/031=gsq
- 户外活动组织的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/pfp=646
- 城市骑行环境的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/vtm=br3
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/045
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/axs
- 社区共享书架的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/aPf
- 城市骑行环境的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/874=vir
- 数字课堂应用的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/knz=528
- 街区绿化养护的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/Uwu=CC1
- 公共服务数字化的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/837
- 乡村产业科普的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/bgd
- 学校食育活动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/ka5
- 城市公共艺术的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/973=emo
- 劳动教育实践的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/kol=788
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1-%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/BPo=n0M
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/335
- 城市生活服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/uly
- 社区防暑服务的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/t4W
- 老年人日常照护的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/081=pse
- 环境监测科普的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/cte=217
- 城市水环境观察的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/dIn=43E
- 儿童安全出行的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/966
- 农村环境治理的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/jhi
- 科学信息获取的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/pYO
- 家庭照护支持的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/162=qrw
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/bgo=424
- 公共空间安全的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90-%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/W6O=44x
- 基层健康服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/785
- 节能家电使用的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/sgt
- 创业经验分享的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/Lxu
- 城市噪声观察的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/530=zzm
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/zhj=162
- 老旧小区改造的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9-%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/oQf=uo8
- 文化场馆预约的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/814
- 城市应急广播的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/dno
- 基层健康服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/6iB
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/194=bpn
- 儿童友好空间的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/hcp=938
- 科学观察活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/ELK=lE4
- 乡村电商实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/745
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/jxd
- 环境监测科普的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/lH7
- 社区生活指南的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/566=vwd
- 城市步行友好的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/zqc=697
- 社区宠物管理的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/iRn=QXa
- 农业科普体验的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/022
- 社区菜市场服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/hsg
- 社区协商议事的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/5yx
- 社区科普课堂的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/128=iek
- 社区体育组织的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/uxn=563
- 数据分析入门的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/U0s=jCf

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
