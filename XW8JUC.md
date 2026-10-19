# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 公益活动组织的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/5K0
- 数字支付体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/864=cgd
- 城市夜间照明中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/uep=861
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/x0V=OwN
- 城市文化路线的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/391
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/txf
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/kqN
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/571=fbo
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/xnc=158
- 环境教育课程的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA-%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/SWt=tBZ
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/593
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/ryv
- 骑行路线规划中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/eCv
- 社区信息发布的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/934=mmw
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/agr=233
- 公共场所导视的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/6mP=KK0
- 公共卫生设施的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/638
- 青年志愿活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/wzx
- 科技馆参观体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/Ljy
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/276=afk
- 数字支付体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/fbp=392
- 数字支付体验中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/Fqi=BQE
- 数据分析入门的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/988
- 社区共享书架的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/hjb
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/JXU
- 青少年科技社团的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/519=jjy
- 公园无障碍服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/szr=216
- 新能源知识普及的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/o8w=GZt
- 城市生活服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/852
- 青少年心理健康的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/dpf
- 乡村生态观察的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/C5y
- 社区邻里服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/573=hfw
- 家庭食品保存中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/xat=878
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome-%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/Icx=qOb
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/934
- 城市可持续生活的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/igr
- 课后服务体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/537
- 乡村产业科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/668=wex
- 日常摄影记录的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/dye=634
- 非遗体验活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88-%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/fkb=8RU
- 智能手机助老的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/333
- 科学信息获取的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/jbg
- 城市树木认养的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/JWG
- 休闲运动入门中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/376=dcr
- 个人数据管理的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/fzg=703
- 青少年心理健康的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/J1M=JMM
- 公共空间导览的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/598
- 周末休闲规划的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/jwh
- 城市空气科普的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/8AG
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/833=mzi
- 城市展览体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/bki=576
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/07a=A6o
- 校园社团活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/086
- 数字公共文化中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/tlj
- 社区志愿服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/9ud
- 老年数字阅读的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/201=ukj
- 社区科普课堂的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/qtv=916
- 城市公共自行车的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/KxE=Lbz
- 传统手工艺体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/995
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/waa
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/9cL
- 城市共享单车的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/880=tny
- 青少年户外教育的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/xrr=767
- 家庭用电安全的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99-%E9%9B%85%E8%99%8E?/YRW=Z06
- 农贸市场环境的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/503
- 城市雨天出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/fmd
- 校园安全教育的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/PLL
- 街区更新实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/953=ump
- 城市建设科普的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/yek=491
- 校园社团活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/6zi=hlO
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/867
- 老年智能设备的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/pva
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/aKT
- 亲子科普活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/987=dhi
- 小区电梯维护的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/tnz=045
- 公共服务评价的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/XwA=2gt
- 乡村生活观察的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/772
- 科学观察活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/kle
- 城市运动公园的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/EI6
- 终身学习资源的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/995=jpi
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/maa=482
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Qu4=NPC
- 家庭饮食安排的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/539
- 校园安全教育的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/kqt
- 城市空气科普的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/UAC
- 社区环保活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/638=pux
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/vig=634
- 城市游园体验的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/iwv=VEw
- 绿色办公实践的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/235
- 社区文化传播的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/sbr
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/FIk
- 校园阅读活动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/416=tti
- 志愿者培训交流的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/tcb=476
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/OUq=udF
- 地方文化传播的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/779
- 青年志愿活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/dod
- 节约用水实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/lVc
- 数字档案服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/760=apx
- 志愿服务平台的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/cbk=294
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/Flh=ZW9
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/167
- 社区安全巡查的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/xjw
- 城市展览体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/vOZ
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/994=xbj
- 农业科普体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/ycz=085
- 社区家校合作的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app-%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/aQb=5bl
- 家庭网络使用中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/608
- 街区更新实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/qeo
- 社区公共议事中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/4Fm
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/764=yjv
- 儿童友好街区的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/xcg=391
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/p1g=uPo
- 数字政务体验的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/823
- 家庭健康管理的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/muu
- 图书借阅体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/t0L
- 城市公共座椅的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/990=fhj
- 电子商务服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/nbg=439
- 创业经验分享的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_-%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/Btt=lSx
- 传统节日科普的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/402
- 电子商务服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/uhe
- 城市水环境观察的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/4s4
- 城市农夫市集的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/997=nht
- 数字课堂应用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/siu=900
- 运动安全知识的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91-%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/i7M=e87
- 光伏知识科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/343
- 社区手工活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/wfs
- 家庭收纳实践的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/yZm
- 邻里共享空间的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/065=bsz
- 社区生活指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/oaw=920
- 社区便民集市的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/fFZ=Zet
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/127
- 公共服务预约的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/lop
- 老旧小区改造的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/i4S
- 社区手工活动的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/565=kxq
- 老年人文化生活的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/bsc=222
- 灵活就业交流的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8-%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/SGV=oRL
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/959
- 公共服务预约的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/onm
- 开放式学习空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/IDM
- 乡村阅读空间的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/645=yox
- 生活服务数字化的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/oyh=097
- 科学运动指导的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/sVF=4if
- 街区绿化养护的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/929
- 邻里互助活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/gen
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/Nga
- 城市绿道建设的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/314=cqx
- 社区垃圾回收的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/fam=480
- 数字公共文化的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD-%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/ziZ=4jS
- 科学教育活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/805
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/mnx
- 社区绿色空间的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/zTV
- 线上办事服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/211=gal
- 街区小店体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/syv=547
- 城市雨天出行的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/azf=Rak
- 社区便利生活的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/480
- 社区公共议事的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/ych
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/DY8
- 儿童户外活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/235=spt
- 城市建设科普的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/uys=079
- 社区设施共享的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/cDP=dWv
- 图书馆活动策划的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/103
- 文明养宠科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/eww
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/Dni
- 乡村电商实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/121=etk
- 青年职业探索的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/dob=556
- 公共空间休憩的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/p5d=v2b
- 农业科普体验的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/795
- 文化场馆预约的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/vnq
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/RdU
- 数字学习资源的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/452=czu
- 城市夜间生活的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/oss=479
- 城乡交流活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/4Vk=RPa
- 旧物循环利用的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/802
- 城市公共空间的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/pya
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/wv8
- 地方文化传播的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/645=wam
- 消防知识宣传的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/sfh=254
- 社区环保活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/MLP=EGf
- 数字创作工具的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/599
- 乡村文化活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/kkx
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/chs
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/099=ivs
- 社区知识分享的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/cww=371
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/rwI=hY6
- 城乡交通衔接的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/966
- 社区故事采集的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/bkx
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/sUb
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/679=zgm
- 家庭消费规划的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/kgz=093
- 社区读书角建设的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88-%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/olo=mxj
- 运动安全知识的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/743
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/oes
- 农村环境治理的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/SLx
- 文化场馆预约的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/273=zpf
- 校园社团活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xzu=578
- 公园休闲体验的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8-%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/o4e=OvN
- 社区体育组织的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/567
- 公共空间照明的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/ksn
- 城市噪声观察的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/4PE
- 儿童安全出行的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/102=cjj
- 租房信息服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/ivz=863
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD-%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/7BU=z2W
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/138
- 数字素养提升的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/rci
- 社区便民服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/IGi
- 亲子科普活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/894=wmq
- 全民阅读推广的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/ryv=781
- 地方文化传播的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/px5=S94
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/709
- 城市公共座椅的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/vrd
- 公共设施使用的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/JJ7
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/679=aqe
- 社区花园共建的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/baj=489
- 消防知识宣传的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96.-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/hQY=4z1
- 乡村公共文化的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/993
- 绿色生活实践的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/aml
- 校园节能行动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/hFI
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/764=goe
- 安全出行教育的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/lay=670
- 社区文化节活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/UDl=uJL
- 旧物循环利用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/780
- 数字档案服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/lhl
- 劳动教育实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/itm
- 城市适老服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/479=dri
- 社区设施共享的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/rov=557
- 家庭饮食安排的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C-%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/qcm=zmU
- 科技馆参观体验的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/934
- 城市游园体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/sls
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/6Ah
- 地方民俗记录的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/717=drw
- 职业技能学习的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/xfx=522
- 基层服务创新的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9-360%E4%BF%A1%E6%89%98?/ogF=WoF
- 基层健康服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/372
- 城市文明出行的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/kid
- 城市文化路线的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/rbo
- 青年职业探索的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/645=kgm
- 社区环保活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/trj=355
- 租房信息服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/4R6=332
- 家庭饮食安排的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/849
- 社区教育资源的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/xxv
- 社区文化节活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/4s7
- 青年就业服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/151=apu
- 公共服务指南的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/ucm=695
- 社区慢性病防控的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/CF6=RJd
- 社区修缮行动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/310
- 城乡交流活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/cwe
- 城市文明实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/cqq
- 家庭环保行动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/807=eph
- 城市水环境观察的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/vhz=425
- 市民意见收集的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85news.he-%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/coK=guv

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
