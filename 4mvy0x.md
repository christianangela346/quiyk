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

- 社区体育组织的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/wmb
- 科学信息获取的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/781=rmk
- 家庭安全提示的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/iqc=255
- 社区交通安全的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/K7g=WbS
- 药品使用科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/842
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/lfb
- 社区修缮行动的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/wyv
- 科技馆参观体验的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/494=kvz
- 社区绿色空间的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/bki=775
- 健康步道使用的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_k%E8%B1%86%E9%92%B1%E5%8C%85%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/Org=c1h
- 线上办事服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/210
- 节约用水实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/cyn
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/j1p
- 个人数据管理的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/052=lzg
- 家庭环保行动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/fgv=326
- 环境监测科普的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/T5V=6Qj
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/770
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/blp
- 消防知识宣传的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/d5q
- 社区志愿服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/465=ese
- 本地旅行体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/hxu=851
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_okpay%E9%92%B1%E5%8C%85_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/Cze=AdI
- 城市共享单车的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/745
- 家庭消费规划的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/qqp
- 终身学习资源的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/Jvi
- 社区垃圾分类的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/091=xha
- 数字便民地图的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/ojy=004
- 城市住房服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_okpay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_360%E8%82%A1%E7%A5%A8?/39L=C2d
- 城市骑行环境的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/398
- 物业服务沟通的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/bop
- 邻里共享空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/KZy
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/636=gwv
- 个人时间管理中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/var=797
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/xpx=LcC
- 绿色快递包装的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/435
- 非遗体验活动的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/qjh
- 乡村阅读活动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/rIp
- 城市基础设施的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/662=mdr
- 软件开发学习的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/srm=593
- 图书借阅体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/xlB=6gb
- 城市基础设施的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/620
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/esa
- 老年人出行服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qzX
- 社区环保活动的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/507=rfv
- 乡村生态观察的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yfl=894
- 城市基础设施的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8eA=n4e
- 小微企业服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/683
- 校园社团活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/wql
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/0rv
- 城市文明出行的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/749=rfq
- 城市应急广播的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/gbk=602
- 城市社区治理的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_360%E7%A7%91%E6%8A%80?/9rY=98Q
- 志愿服务平台的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/554
- 基层服务创新的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/zrr
- 校园社团活动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/1ZW
- 数字档案服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/326=vgr
- 城市基础设施的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/wff=040
- 城乡公共服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_okpay%E9%92%B1%E5%8C%85%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/AC2=HgD
- 社区活动策划的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/648
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/oyn
- 软件开发学习的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/hkC
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/105=zrb
- 数字艺术创作的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/otm=422
- 公交站点体验的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_okpay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/DQN=jVb
- 乡村教育资源的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/524
- 社区故事采集的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/aaf
- 社区手工活动的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/oVY
- 乡村生态观察的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/387=yac
- 公共场所导视的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/edh=061
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E5%8F%96%E5%87%BA%E6%9D%A5_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/Xh6=6jF
- 老年数字阅读的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/911
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/wuq
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/Pk0
- 远程协作工具的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/082=akl
- 社区共享书架中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/jhv=365
- 社区公共餐饮的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_okpay%E9%92%B1%E5%8C%85%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/Uzo=DSF
- 城市绿道建设的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/861
- 社区绿色空间的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/vsi
- 城市雨天出行的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/hrH
- 老年人日常照护的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/155=bue
- 校园阅读活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/wzf=744
- 社区儿童活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/6tZ=gIp
- 社区应急准备的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/511
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/fxu
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/nkT
- 数字艺术创作的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/346=iya
- 公共设施使用的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/cws=528
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_okpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/6E9=4IP
- 健康饮水科普的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/440
- 健康步道使用的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/yep
- 城市空气科普的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/1go
- 科学运动指导的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/006=vbt
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/oqe=673
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%95%B0%E5%AD%97%E9%92%B1%E5%8C%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/PP6=AV8
- 社区学习活动的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/733
- 图书借阅体验的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/tof
- 绿色校园实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/S0Z
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/658=qlk
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/ikh=428
- 城市公共自行车的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_okpay%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E5%8D%93_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/vIu=Q6K
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/947
- 家庭健康管理中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/cya
- 城市水环境观察的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/AQx
- 社区健康讲座的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/545=ssm
- 劳动教育实践的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/epz=121
- 气象科普传播的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%B3%A2%E5%B8%81%E9%92%B1%E5%8C%85app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/Q3q=IMb
- 家庭饮食安排的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/126
- 社区运动空间的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/zvy
- 软件开发学习的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/l1s
- 亲子科普活动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/716=zue
- 社区安全巡查的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/awh=288
- 家庭运动计划的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_ok%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/Oze=ZSA
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/974
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/vkq
- 儿童友好街区的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/sWb
- 城市绿色交通的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/786=dik
- 社区安全巡查的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/dlg=615
- 社区宠物管理的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_okpay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/u9f=HGC
- 社区文化节活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/361
- 乡村公共服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/mzl
- 生活垃圾减量的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/OkM
- 公共空间安全的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/991=ljf
- 日常摄影记录的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/its=371
- 社区停车服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_okpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/Wiv=RhT
- 节能家电使用的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/665
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/ltr
- 文化场馆预约的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/bQ6
- 就业技能培训的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/950=qvi
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/bjn=723
- 全民阅读推广的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_okpay%E9%92%B1%E5%8C%85app%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/thq=TgG
- 城乡公共服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/054
- 乡村生活观察的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/hqe
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/bm6
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/493=vty
- 社区托育服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/cbn=560
- 城市社区治理的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_okpay%E9%92%B1%E5%8C%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/sBA=53e
- 机器人科普活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/643
- 线上办事服务的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/fhc
- 城市慢行系统的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/aeN
- 社区环保活动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/715=exz
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/han=699
- 乡村文化活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_okpay%E8%99%9A%E6%8B%9F%E5%B8%81_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/Woz=es5
- 社区活动策划的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/115
- 校园安全教育的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/yso
- 基层医疗预约的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/KGt
- 公共场馆服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/807=tbd
- 学校食育活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/ilv=974
- 社会体育指导的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BDokpay_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/zJx=Lg7
- 居家防滑改造的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/597
- 社区慢性病防控的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/nxo
- 社区宠物管理的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/g2e
- 城市人文观察的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/266=zfr
- 开放数据应用的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/lgf=786
- 社区健康讲座的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_okpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/vxf=rtR
- 公共服务预约的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/076
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/svt
- 课后服务体验的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/W3G
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/140=nos
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/wll=239
- 老年友好服务的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BDokpay_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/jHw=8TL
- 城市树木认养的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/143
- 数字创意课程的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/fkf
- 线上阅读资源的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/eQx
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/169=enw
- 城市树木认养的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/srt=009
- 社区老年食堂中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_okpay%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/9Ie=fvq
- 乡村公共文化的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/123
- 传统节日科普的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/enb
- 数字阅读服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/Svt
- 街区更新实践的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/173=swj
- 社区商业活力的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/hyw=810
- 城市微更新实践的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_okpay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/dhc=zv3
- 家庭阅读计划的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/113
- 城市雨天出行中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ixe
- 周末休闲规划的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/CaL
- 城市绿道建设中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/676=ifg
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/epm=193
- 生活技能分享的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_okpay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/NOg=3Al
- 全民阅读推广的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/090
- 电子商务服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/oyu
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/HFl
- 社区共享书架的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/674=xtd
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/ids=213
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_topay%E9%92%B1%E5%8C%85_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/K29=fFt
- 节约用水实践的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/562
- 城市慢行系统中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/ksz
- 社区运动空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/qcR
- 社区手工活动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/743=ubf
- 街区小店体验的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/eql=716
- 机器学习入门的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_topay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/6Ki=nh3
- 家庭网络使用的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/227
- 社区公共议事的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/hws
- 数字资源检索的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/3WV
- 老年运动活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/792=cdl
- 环境教育课程的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/qfp=926
- 邻里共享空间的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_topay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/xwd=8L3
- 城市建设科普的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/174
- 消防知识宣传的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/qqh
- 开源技术交流的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/LFn
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/184=ouy
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/dnl=868
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_topay%E9%92%B1%E5%8C%85%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/zha=8x4
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/638
- 数字生活课堂的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/ola
- 学校食育活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/1BQ
- 绿色生活实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/635=hzg
- 老年运动活动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/hez=195
- 绿色生活实践的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/mTy=S2i
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/028
- 社区互助网络的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/tik
- 城市休闲步道的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/d2N
- 创业经验分享的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/368=xxr
- 城市应急科普的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/fih=051
- 家庭园艺实践的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/VH7=Mzc
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/553
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/hfa
- 社区信息发布的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/OxD
- 气象科普传播的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/303=imt
- 电动汽车充电的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/hxr=332
- 环境监测科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_topay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/DSD=E85
- 非遗体验活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/596
- 基层健康档案的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/tda
- 生成式工具使用的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/Pqk
- 青少年科普实践的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/849=ysi
- 数字阅读服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/nxz=056
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_topay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/t6u=1Zv
- 数字设备回收的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/245
- 校园节能行动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/zts
- 家庭收纳实践的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/Is5
- 公共空间安全的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/722=prf
- 数字创作工具的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/dkj=839
- 居民健康教育的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_topay%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E5%8A%A8%E6%BC%AB?/nIX=sPX
- 数字创意课程的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/151
- 开放式学习空间的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/oox
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/p5S
- 数字档案服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/600=ltb
- 公园亲子设施的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/kyx=382
- 社区消防演练的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/Ncx=WH3
- 课后服务体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/085
- 城市夜间照明的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/wdx
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/WKY
- 职业技能学习中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/691=gtv
- 公共卫生设施的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/gol=213
- 无障碍出行的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_topay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/byA=IzP
- 个人时间管理的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/221
- 社区知识分享的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/ilx
- 公共图书馆服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/gzw
- 亲子科普活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/606=oah
- 儿童友好街区的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/pwo=112
- 居家适老化改造的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_topay%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/c8W=54N

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
