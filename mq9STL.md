# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:20**

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

- 社区互助网络的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8767%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD1.0.8_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/iws=469
- 社区读书角建设的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8767%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD1.0.8_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/PVz=LcM
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/372
- 儿童友好空间的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/lzg
- 居民健康教育的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/xWH
- 数字阅读服务的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/042=uns
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/pcr=877
- 社区休闲设施中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%B1_360%E6%8E%A2%E6%BA%90?/cN9=VNY
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/683
- 青年志愿活动的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/awh
- 家庭节能实践的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/6Y3
- 科学观察活动的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/597=ktr
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/urh=427
- 社区活动报名的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_5g%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/ZLW=Qb4
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/579
- 数字艺术创作的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/ont
- 小区电梯维护的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/RcH
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/694=iqn
- 社区活动空间的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/vao=445
- 开放数据应用的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758c%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/GZy=Fdv
- 城市公共标识的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/594
- 社区活动策划的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/atb
- 线上办事服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/Z4v
- 健康饮食教育的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/559=qbk
- 城市展览体验的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/iqw=296
- 志愿者培训交流的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/7ch=reK
- 社区文化节活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/175
- 新能源出行中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/ekm
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/f55
- 街区更新实践的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/010=eok
- 农业科普体验的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/chl=872
- 城市人文观察的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_2020%E6%9C%80%E6%96%B0%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8656%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/LhU=fVX
- 绿色出行服务的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/321
- 社区便民集市的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/mjl
- 社区休闲设施的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/bk7
- 城市住房服务的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/077=qpb
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/dch=289
- 家庭节能实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/eLe=ia8
- 物业服务沟通的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/535
- 街道综合服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/kqp
- 社区生活指南的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/7dv
- 开源技术交流的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/952=urh
- 乡村产业科普的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/nli=671
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/qFF=YaI
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/582
- 数字生活课堂的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/zww
- 社区阅读服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/VCO
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/556=ytx
- 家庭饮食安排的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/kec=683
- 节气饮食文化的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/eY7=xiB
- 数字资源检索的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/012
- 城市体育设施中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/wir
- 社区公共餐饮的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/xIh
- 公共设施使用的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/402=zam
- 应急物资管理的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/zvk=159
- 儿童运动体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/J17=wC8
- 城市生活记录的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/069
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/kvb
- 家庭健康科普的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/mlT
- 社区消防演练的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/634=fvs
- 数字地图应用的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/bld=596
- 软件开发学习的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_360%E7%9B%B4%E6%92%AD?/PH8=EU9
- 城市可持续生活的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/392
- 开放式学习空间的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/jye
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/EzM
- 社区家校合作的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/464=oba
- 社区互助网络的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/con=521
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/sZ6=uIy
- 开源技术交流的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/586
- 老年运动活动的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/epu
- 便民服务窗口的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/BlH
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/122=mcn
- 社区活动空间的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/wpc=879
- 网络信息辨识的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/1hf=JUs
- 社区运动空间的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/716
- 家庭消费规划的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/dmg
- 社区便民服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/xwm
- 公共场馆服务的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/922=mae
- 青年志愿活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/svz=701
- 城市住房服务的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/Prm=chI
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/396
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/jpa
- 数字档案服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/rSX
- 社区家校合作的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/286=puf
- 城市噪声观察的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/gxb=811
- 生活技能分享的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%97%AE%E5%8D%B7?/3GB=bWs
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/189
- 儿童运动体验的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/qth
- 数字艺术创作的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/oBu
- 社区绿色空间的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/705=cal
- 社区设施共享的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/jvg=332
- 数字素养提升的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/5rg=Co8
- 城市公共标识的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/904
- 公共场所导视的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/vtt
- 家庭运动计划的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/75X
- 数字艺术创作的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/431=fwg
- 创业经验分享中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/zae=313
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/H7b=Ej8
- 租房信息服务的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/139
- 科学运动指导的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/jmu
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/qpr
- 节日文化体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/372=fmq
- 地方旅游导览的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/yqe=836
- 社区商业活力的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/DDR=kUd
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/397
- 线上办事服务的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/anx
- 校园社团活动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/9Eb
- 社区活动报名的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/807=hsv
- 消防知识宣传的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/wst=034
- 小微企业服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/xPw=WHC
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/921
- 在线教育体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/yed
- 城市微更新实践的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/AUE
- 城市住房服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/280=etl
- 社区活动策划的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/yqs=219
- 电子商务服务的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/hPV=WtC
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/270
- 社区家校合作的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/zex
- 社区科普课堂的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/8WE
- 城市雨天出行的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/658=iwc
- 数据分析入门的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/ofw=152
- 城市人文观察的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/wYm=jaP
- 儿童户外活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/109
- 软件开发学习的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/plt
- 城市公共厕所的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/DeM
- 街区绿化养护的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/057=syb
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/hxv=714
- 节约用水实践的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/XD9=Zti
- 科技馆参观体验的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/182
- 药品使用科普的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/gal
- 乡村教育资源的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/Ulb
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/261=qic
- 家庭节能设备的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/sck=619
- 家庭防灾准备的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/hVa=FHW
- 城市住房服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/395
- 城市适老服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/cza
- 农贸市场环境的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/pIZ
- 绿色出行服务的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/407=nbs
- 乡村教育资源的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/kpm=274
- 无障碍出行的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/Csc=2z3
- 开放数据应用的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/011
- 社区老年食堂的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/vdi
- 生成式工具使用的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/1lG
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/528=ies
- 食品安全科普的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/izm=890
- 个人信息保护的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/zMD=OfQ
- 机器人科普活动的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/242
- 儿童友好空间的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/hhs
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/olK
- 便民服务窗口的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/365=nxt
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/hzz=748
- 儿童安全出行的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/zTz=tw4
- 小区停车协商的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/970
- 数字政务体验的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/qap
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/3Mk
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/773=skv
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/wir=274
- 电动汽车充电中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/Zmm=XNJ
- 人工智能科普的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/646
- 电子商务服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/mvj
- 绿色出行服务的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/CFI
- 青年就业服务的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/563=lds
- 便民维修服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/xyj=060
- 社区便民集市的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/Lim=39X
- 社区家政服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/349
- 地方美食文化的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/end
- 学校体育活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/Lvr
- 社区商业活力的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/084=ugc
- 城市雨天出行的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/gwj=717
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/sY2=taN
- 乡村阅读空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/126
- 社区环保活动的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/bxc
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/LDW
- 城市绿色交通的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/726=ovv
- 农业科普体验的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/sux=136
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/qPR=HPe
- 儿童友好空间的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/241
- 食品配送体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/zuk
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/C6G
- 家庭防灾准备的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/812=rhv
- 科学信息获取的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/mzb=492
- 社区公共议事的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/TXV=2vY
- 小区停车协商的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/229
- 绿色办公实践的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/cvb
- 校园安全教育的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/0B8
- 青年志愿活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/150=lnj
- 社区消防演练的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/cjl=545
- 城市社区治理的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/Obq=9p6
- 城市农夫市集的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/352
- 家庭环保习惯的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/aet
- 街区小店体验的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/UBP
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/748=znd
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/bbx=095
- 市民意见收集的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/ghH=OP2
- 健康饮水科普的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/582
- 家庭食品保存的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/nih
- 社区知识分享的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/QYY
- 地方美食文化的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/993=tfe
- 城乡公共服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/asv=721
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/PKI=zUK
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/531
- 周末休闲规划的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/ivz
- 绿色消费选择的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/1ie
- 街区绿化养护的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/922=omf
- 青少年户外教育的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/rcw=337
- 城市适老服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/kfx=7WX
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/103
- 家庭志愿活动的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/kic
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/Sx3
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/687=nmf
- 乡村文化活动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/rsi=325
- 老年人日常照护的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/AKa=0J0
- 家庭饮食安排的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/721
- 街区更新实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/hiu
- 城市展览体验中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/c4l
- 节假日出行安排的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/748=nvr
- 社区生活指南的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/voh=821
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/GaB=2oK
- 社区商业活力的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/610
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/xfl
- 数字艺术创作的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/2MA
- 传统节日科普的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/429=ixf
- 社区安全巡查的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/ify=272
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/QnD=0fh
- 健康饮食教育的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/907
- 社区艺术活动的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bbu
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Asg
- 社区家政服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/559=gqp
- 城市公共座椅的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mgq=254
- 公共文化活动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3FK=8jk
- 文化讲座服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/757
- 数字政务体验的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/krd
- 公共交通接驳的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/PXU
- 旧物循环利用的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/395=kpo
- 社区文化节活动的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/nnv=931
- 无障碍出行的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/EWH=bto
- 个人数据管理的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/947
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/qti
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/DqP
- 社区便利生活的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/325=wtf
- 数字政务体验的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/dpu=510
- 食品配送体验的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/IuG=VCv
- 家庭理财科普的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/418
- 儿童运动体验的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/bin
- 公交无障碍服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/UkQ
- 就业技能培训的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/995=exc
- 公共空间安全的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/twf=964
- 乡村文化空间中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/dLm=R3l
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/329
- 社区运动空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/sug

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
