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

- 城市住房服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/hvk
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/422=aln
- 社区防暑服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/nyx=783
- 数字创作工具的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/pau=3Ki
- 城市公共厕所的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/814
- 城市便民驿站的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/wrc
- 就业技能培训的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/wS4
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/639=oav
- 城市微更新实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/lbh=346
- 光伏知识科普的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/xpG=X0g
- 科学教育活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/891
- 社区设施共享的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/evz
- 数字公共文化的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/lD5
- 公共服务评价的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/818=gda
- 城市休闲步道的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/zvk=440
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88qq-%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/WfM=aSv
- 乡村公共阅读的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/067
- 校园社团活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/vmj
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/avp
- 城市文明实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/245=cmq
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/qrs=059
- 社区协商议事的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88QQ-%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/BaP=Aqc
- 小区公共照明的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/995
- 家庭运动计划的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/mxv
- 城市基础设施的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/ikR
- 居家适老化改造的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/537=rxn
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/ptc=976
- 青少年科技社团的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%AF%BC%E5%B8%88%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80-%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/8HR=8Bq
- 志愿者培训交流的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/306
- 公共场所导视的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/gtj
- 社区学习活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/uNb
- 急救知识普及的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/374=mjl
- 家庭环保行动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/oyf=356
- 社区托育服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/70g=cfR
- 亲子阅读活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/242
- 便民服务窗口的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/adt
- 社区环保活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/VG8
- 社区教育资源的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/986=tdi
- 城市应急广播的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/pqa=889
- 城市水环境观察的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E7%BB%8F%E5%85%B8%E8%AF%9D%E6%9C%AF%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/x6u=Jqm
- 家庭运动计划的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/919
- 物业服务沟通的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/bne
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/Cwe
- 城市生活记录的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/419=sbd
- 文化讲座服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/jxm=599
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E7%9A%84%E9%A3%8E%E9%99%A9-%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/UH0=Mao
- 社区安全巡查的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/679
- 社区便民服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/mpw
- 数字生活课堂的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/Z7Q
- 社区应急准备的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/273=aij
- 日常摄影记录中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/adu=079
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E5%90%A6%E7%9C%9F%E5%AE%9E%E5%AD%98%E5%9C%A8-%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/H87=bL9
- 儿童运动体验的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/955
- 城市人文观察的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/aay
- 公共设施维护的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/OyF
- 户外活动组织的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/028=mom
- 新能源出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/mks=745
- 儿童友好空间的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%93%E4%B8%9A%E5%B8%A6-%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/tLs=VRu
- 公园无障碍服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/866
- 租房信息服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/yvw
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/gJa
- 公共服务指南的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/663=oto
- 社区学习活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/ynr=905
- 本地历史资料的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AF%BC%E5%B8%88-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/vWs=AjZ
- 科学健身方法的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/735
- 节日文化体验的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/rch
- 数字档案服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/nXQ
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/001=ehd
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/pwc=141
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A96%E5%A8%B1%E4%B9%90-%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/uVu=YQ7
- 旧物循环利用的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/275
- 家庭收纳实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/svn
- 学校食育活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/EZT
- 公交站点体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/269=lsq
- 无障碍出行的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/uko=873
- 老年数字阅读的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B8%88%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9-%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/bT4=2oa
- 文化讲座服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/054
- 城乡交流活动的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/pzf
- 物业服务沟通的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/adB
- 物业服务沟通的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/679=bcz
- 社区知识分享的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/yim=583
- 社区手工活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E7%BE%A4-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/Ajg=jPk
- 家庭运动计划的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/589
- 生成式工具使用的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/pjz
- 社区邻里服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/5d4
- 青年志愿活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/256=skq
- 数字支付体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/qtb=381
- 绿色建筑理念的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%85%A7%E7%9C%BC?/YaB=M16
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/247
- 社区活动空间的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/gfz
- 社区环保活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/di1
- 青年职业探索的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/963=vgu
- 学校食育活动的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/xad=973
- 创业经验分享的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%90%88%E4%BD%9C-%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/SFn=aQy
- 数字素养提升的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/000
- 社区读书角建设的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/kyd
- 青少年心理健康的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/dQO
- 街区道路维护的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/849=ebf
- 开源技术交流的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/cwp=793
- 城市公共自行车的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/w6g=Rug
- 城市雨天出行的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/727
- 城市应急广播的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/cba
- 公共设施维护的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/4EP
- 城市公共艺术的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/718=ccu
- 课后服务体验的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/xoo=634
- 公共服务评价的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/QGb=2bS
- 家庭科学教育的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/152
- 职业技能学习的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/hzs
- 青年就业服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/1uE
- 志愿者培训交流的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/478=ome
- 街区更新实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/tts=184
- 非遗课堂体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/MZH=Twv
- 居民健康教育的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/821
- 文化场馆预约的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/fal
- 灵活就业交流的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/drJ
- 城市公共自行车的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/935=azd
- 城市农夫市集的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/yqu=266
- 青年志愿活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A20%25%E7%9A%84%E4%B8%93%E4%B8%9A%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/2h3=8EK
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/745
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/kec
- 数字设备回收的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/3Dr
- 家庭健康科普的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/145=rvm
- 新能源出行的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/gtc=450
- 城市游园体验的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87-%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/cMq=EV5
- 社区防暑服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/478
- 户外活动组织的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/huz
- 课后服务体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/En9
- 社区老年食堂的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/251=axz
- 社区托育服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/plp=852
- 社区商业活力的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E8%83%BD%E6%9C%88%E5%85%A5%E4%B8%8A%E4%B8%87%E5%90%97-%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/Uer=cSm
- 家庭网络使用的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/795
- 居民健康教育的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/uxq
- 安全出行教育的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/svp
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/800=out
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/xyc=518
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%A2%86%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/z0k=XNn
- 科学信息获取的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/756
- 绿色校园实践的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/rze
- 市民意见收集的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/akj
- 城市步行友好的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/975=cpr
- 科学运动指导的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/cjj=623
- 青少年心理健康的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E7%BD%91%E9%92%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A5%97%E8%B7%AF-%E5%BF%85%E5%BA%94%E8%A7%A3%E5%AF%86?/5fC=Uhr
- 城市游园体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/483
- 社区儿童活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/lcl
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/uxU
- 公共卫生宣传的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/804=hnj
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/spk=191
- 健康步道使用的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%8D%95%E8%B5%9A%E9%92%B1-%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/4jr=OHM
- 城市绿色交通的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/656
- 数字创意课程的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/vyq
- 社区文化传播的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/doG
- 城市骑行环境的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/078=njx
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/emg=314
- 口袋公园建设的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/bCd=6hJ
- 网络安全教育的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/269
- 数字政务体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/hpj
- 社区学习活动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/8RI
- 社区花园共建的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/861=xtg
- 健康饮食教育的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/wuk=852
- 数字地图应用的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E6%8C%A3%E9%92%B1-%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/mPS=VEq
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/592
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/eth
- 基层健康档案的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/EEG
- 公共服务评价的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/616=jgt
- 城市共享单车的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/xvv=022
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_app%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/ZoW=5D5
- 社区运动空间的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/545
- 绿色出行服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/jwz
- 儿童阅读角的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/pIq
- 休闲运动入门的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/510=dpv
- 数字阅读服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/hjb=448
- 基层医疗预约的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%9D%A0%E8%B0%B1%E5%90%97-%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/shq=Hzx
- 远程协作工具的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/178
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/uqc
- 老年智能设备的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/Nk2
- 社区共享书架的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/045=ddb
- 生活垃圾回收的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/ygv=241
- 人工智能科普的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%97%A5%E6%8C%A3100%E5%85%83%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%B0%8F%E5%85%BC%E8%81%8C-%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/9jd=kiw
- 城市公共空间的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/760
- 开放式学习空间的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/vin
- 城市共享单车的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/HKS
- 邻里互助活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/202=hcc
- 城市文明实践中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/ktx=031
- 城市公共饮水的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%AF%8F%E5%A4%A9%E8%B5%9A%E7%82%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/ep8=RRm
- 公共交通接驳的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/302
- 小微企业服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/adu
- 社区志愿服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/uhV
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/356=yud
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/uhq=179
- 社区协商议事的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/uMB=2Gy
- 儿童户外活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/739
- 健康饮水科普中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/vhk
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/sEM
- 家庭健康科普中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/985=okl
- 气象科普传播的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/zkm=735
- 城市文化路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BF%AB3%E7%BD%91%E5%9D%80-36%E6%B0%AA%E8%B5%84%E8%AE%AF?/RmL=aLH
- 数字生活课堂的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/075
- 城市社区治理的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/ags
- 社区垃圾回收的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/u3H
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/096=mni
- 社区法律科普的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/aof=680
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%85%85%E5%80%BC10%E5%85%83%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/KUc=cc0
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/915
- 社区文化传播的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/icp
- 地方美食文化的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/8ez
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/884=uyo
- 城市文明出行的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/svf=564
- 家庭消费规划的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B5%8F%E5%B8%AE%E8%B5%9A%E7%B1%BB%E4%BC%BC%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/Kco=Z2N
- 信息无障碍体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/786
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/myd
- 基层服务创新的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/BFg
- 城市休闲步道的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/732=mag
- 公共服务数字化的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/qdr=451
- 课后服务体验的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/QS4=YN3
- 健康饮水科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/812
- 数字学习资源的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/cyc
- 社区互助网络的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/Njb
- 数字创作工具的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/538=ejr
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/yuz=864
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/phX=9qJ
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/919
- 乡村公共文化的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/keo
- 青少年心理健康的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/oXN
- 口袋公园建设的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/392=ibk
- 街区更新实践的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/vhd=685
- 学校体育活动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88-%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/CGQ=kwS
- 学校体育活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/504
- 社会体育指导的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/ixv
- 儿童友好街区的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/vUs
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/300=ayf
- 社区停车服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/smy=935
- 街区更新实践的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/RG8=kSX
- 乡村文化空间的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/914
- 城市住房服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/ifw
- 城市社区治理的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/f9i
- 公共场所导视的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/356=ccc
- 城市生活服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/ckc=043
- 市民热线服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E5%8F%B7-%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/pLR=ENx
- 跨代沟通活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/065
- 本地历史资料的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/vru
- 公共空间休憩的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/DY4
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/653=wtz
- 科普展览体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/tjk=560
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/DmD=1C0
- 数字政务体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/691
- 城市文化路线的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/lpi
- 家庭饮食安排的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/h1S
- 街区更新实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/121=gvo
- 家庭节能实践中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/wou=058
- 传统节日科普的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%BE%AE%E4%BF%A1-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/to7=aMI

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
