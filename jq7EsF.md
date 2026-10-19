# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 社区志愿服务的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_360%E6%B1%87%E5%B8%82?/ynt=362
- 城市展览体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_360%E6%B1%87%E5%B8%82?/RMe=zkU
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/209
- 数字生活课堂的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/dxq
- 生活服务数字化的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/IUF
- 城市慢行系统的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/793=yij
- 社区信息发布的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/hxb=278
- 街区道路维护的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/4kx=XvW
- 开放式学习空间的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/736
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/nrk
- 灵活就业交流的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/z5H
- 数字支付体验的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/795=rcl
- 就业技能培训的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/orp=272
- 城市公共饮水的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/2LW=zlG
- 本地消费场景的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/462
- 文化讲座服务的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eya
- 市民意见收集的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/a8f
- 青年志愿活动的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/029=atv
- 儿童安全出行的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/swl=831
- 城市生活记录的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/GRa=F7f
- 基层健康档案的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/331
- 数字创意课程的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/mwk
- 校园社团活动中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/Tij
- 家庭用电安全的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/763=wpl
- 社区老年食堂的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/uko=119
- 城市适老服务的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/r1a=TLu
- 数字艺术创作的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/930
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/cgj
- 开放数据应用的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/gq3
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/042=nuo
- 本地旅行体验的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/oww=909
- 社区手工活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/cqr=mTT
- 社区心理支持的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/673
- 网络安全教育的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/qfh
- 智能手机助老的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/prZ
- 物业服务沟通的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/512=mfi
- 城市慢行系统的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/moy=146
- 口袋公园建设的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/MHI=iJS
- 乡村文化空间的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/433
- 科学运动指导的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/gox
- 街头绿植养护的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/rNS
- 社区健康讲座的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/562=cbm
- 数字设备回收的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/ugb=672
- 城市展览体验的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/VYF=p17
- 城市公共标识的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/170
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/vnd
- 公共服务数字化的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/7wY
- 老年学习活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/972=sxi
- 地方戏曲体验的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/dar=518
- 基层服务创新的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/Ee8=LPD
- 老年友好服务的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/394
- 生成式工具使用中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/juc
- 家庭养老规划的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/soX
- 创业经验分享的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/259=acf
- 社区老年食堂的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/tuv=764
- 家庭网络使用的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/1pE=xb1
- 家庭环保行动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/290
- 公共服务沟通的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/djp
- 社区文化传播的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/TKI
- 城市展览体验的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/971=zma
- 公共服务咨询的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/din=680
- 乡村文化空间的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/veu=izM
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/556
- 城市共享单车的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/pwn
- 家庭教育交流中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/eNM
- 数字设备回收的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/555=otu
- 家庭节能实践的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/dwk=637
- 公共服务咨询的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E5%9F%BA%E9%87%91?/twQ=D0I
- 数字艺术创作的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/180
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/sgs
- 社区托育服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/voq
- 社区便民集市的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/073=enk
- 乡村文化活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/jnt=655
- 社区法律科普的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/vBm=tsT
- 社区科普课堂的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/981
- 社区设施共享的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/pzz
- 读书会组织的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/HQC
- 读书会组织的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/848=ixk
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/cpx=537
- 新能源知识普及的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/QO8=R65
- 公共服务预约的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/162
- 急救知识普及的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/ssp
- 城市绿道建设的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/Tpa
- 读书会组织的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/083=rdj
- 家庭收纳实践的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/ffh=214
- 老年运动活动的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/qqZ=jTv
- 绿色办公实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/326
- 城市游园体验的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/uhp
- 乡村生活观察的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/lik
- 公共设施维护的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/654=cdb
- 儿童友好街区的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/dto=073
- 社区知识分享的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/FKW=x88
- 农村环境治理的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/360
- 数字便民地图的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/eiu
- 社区学习活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/snO
- 城乡交通衔接的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/072=tak
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/ltb=035
- 本地历史资料的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/lnK=9qy
- 低碳社区实践的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/238
- 公共交通接驳的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/nqx
- 数字公共文化中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/RnL
- 社区停车服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/613=wwn
- 科学观察活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/wyc=565
- 社区便利生活的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/bSw=2tO
- 便民维修服务中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/388
- 公共空间导览的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/viu
- 绿色消费选择的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/Ujz
- 城市文明出行的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/996=nov
- 智慧停车服务的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/hzf=534
- 城市公共空间的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/GXM=oAf
- 城市水环境观察的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/523
- 公共卫生宣传的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/wpn
- 开放数据应用的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/H9h
- 街区小店体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/854=eqb
- 个人数据管理的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/gtg=201
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/UJ6=YGn
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/535
- 科学教育活动的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/lgv
- 乡村公共服务中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/5rM
- 社区体育组织的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/039=mek
- 乡村公共阅读的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/aze=671
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/2BR=eZc
- 公共健身器材的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/171
- 城市便民驿站的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/yxa
- 日常摄影记录的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/0jD
- 租房信息服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/393=gys
- 绿色校园实践的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/zst=780
- 城市住房服务的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E5%93%94%E5%93%A9?/nmX=dju
- 文化场馆预约的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/246
- 线上办事服务的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/fma
- 社区信息发布的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/o6S
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/886=drm
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/xki=613
- 开放式学习空间的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/vdA=lsh
- 居家防滑改造的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/602
- 家庭用电安全的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/wee
- 家庭环保行动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/vi8
- 智慧停车服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/294=lvb
- 信息无障碍体验的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/pnj=285
- 青少年科普实践的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/FKd=GNH
- 光伏知识科普的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/640
- 日常摄影记录的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/qxg
- 个人信息保护的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/MPy
- 校园节能行动的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/431=enn
- 个人信息保护的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/mqn=083
- 家庭健康管理的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/jLr=FTV
- 城市空气科普的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/582
- 就业技能培训的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/vek
- 社区学习活动的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/u4B
- 社区便民集市的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/650=vcm
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/myx=807
- 软件开发学习的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/4jF=ac1
- 社区绿色空间的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/203
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/ofx
- 社区商业活力的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/Vuw
- 灵活就业交流的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/097=dau
- 城市公共厕所的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/gib=571
- 公共场所导视的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/YWx=mri
- 食品安全科普的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/711
- 城市地名文化的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/uvx
- 社区邻里服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/bjH
- 无障碍出行的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/035=nvj
- 社区文化传播的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/wak=428
- 城市慢行系统的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/MIn=K6s
- 科学信息获取的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/489
- 骑行路线规划的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/vti
- 城市文明实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/uvW
- 社区法律科普的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/817=pbu
- 青年志愿活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/djz=949
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/TQg=YTK
- 数字档案服务的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/097
- 绿色办公实践的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/erb
- 儿童友好街区的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/2Uj
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/087=eau
- 家庭阅读计划的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/mrd=509
- 小微企业服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/VkA=5Pf
- 社区快递服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/072
- 城市微更新实践的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/zkx
- 家庭阅读计划的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/JWn
- 儿童友好空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/910=rnj
- 老年智能设备的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/srg=483
- 在线教育体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/a9H=Srq
- 读书会组织的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/066
- 数字艺术创作的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/gst
- 城市慢行系统的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Fdw
- 城市步行环境的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/491=fwx
- 青少年科普实践的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/vaq=775
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/m1L=Jes
- 气象科普传播的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/065
- 乡村文化空间的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/aei
- 绿色快递包装的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/zz7
- 智慧停车服务的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/423=ccx
- 本地消费场景的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/vso=086
- 数字设备回收中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/YVn=Dpt
- 农产品品牌传播的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/489
- 城市公共艺术的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/cgl
- 社区信息发布的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/sTU
- 儿童户外活动的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/095=htj
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/exc=854
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/DdC=JSE
- 绿色办公实践的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/560
- 数字政务体验的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/fgb
- 读书会组织的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/j0J
- 家庭健康科普的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/441=vje
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/lhb=636
- 城市文明实践的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/DT6=u3W
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/018
- 公共卫生设施中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/nhv
- 城市农夫市集的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/th3
- 无障碍出行的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/078=vik
- 社区宠物管理的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/oea=176
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/4S2=i42
- 城市农夫市集的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/987
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/yby
- 公共服务咨询的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/D63
- 绿色办公实践的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/582=jsj
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/psp=899
- 光伏知识科普的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/812=JQS
- 社区协商议事的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/964
- 城市树木认养的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/zuw
- 学校食育活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/azd
- 健康饮食教育的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/851=dmv
- 节能生活方式的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/kqb=810
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/61U=Yuq
- 数字生活课堂的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/963
- 青年职业探索的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/nno
- 周末休闲规划的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/FMf
- 城市公共饮水的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/416=lfe
- 小微企业服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/dex=322
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/QBZ=xiu
- 家庭健康管理中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/441
- 社区防暑服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/jnz
- 数字素养提升的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/mU5
- 老旧小区改造的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/863=rbo
- 就业技能培训的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/xtp=848
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/ZD8=Vz0
- 城市人文观察的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/471
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/gdp
- 急救知识普及的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/bNb
- 家庭阅读计划的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/691=htx
- 数字支付体验的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/hav=900
- 地方民俗记录的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/9Kx=thj
- 校园阅读活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/600
- 绿色出行服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/zqd
- 城乡交流活动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/JIX
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/339=edn
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/bwo=101
- 数字创意课程的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_10%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/Jon=jVZ
- 机器学习入门的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/855
- 城市共享单车的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/epl

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
