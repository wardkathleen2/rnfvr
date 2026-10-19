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

- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/qqo=013
- 线上办事服务的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/DbH=rGr
- 机器人科普活动的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/254
- 数字便民地图的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/snj
- 社区便利生活的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/U5G
- 邻里互助活动的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/751=qfk
- 乡村阅读空间的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/xka=266
- 城市博物馆服务的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91888%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/1Qf=gCs
- 文明养宠科普的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/706
- 安全出行教育的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/bag
- 社区家政服务的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/2Po
- 气象科普传播的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/153=qwa
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/mjc=462
- 校园阅读活动的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91app_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/T6a=OGA
- 社区快递服务的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/874
- 数字创意课程的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/dmd
- 社区科普课堂的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/dOw
- 个人时间管理的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/879=qxf
- 城市公共厕所的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/ggs=865
- 老年学习活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/N0x=6dI
- 数字艺术创作的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/245
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/eas
- 老年智能设备中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/9SJ
- 城市步行友好中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/099=efs
- 乡村公共服务的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/wro=891
- 校园社团活动的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8iosapp_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/5ZI=3Ru
- 家庭照护支持的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/901
- 城市社区治理的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/jbb
- 公共空间安全的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/FBO
- 社区绿色空间的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/570=vic
- 社会体育指导的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ody=648
- 社区法律科普的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91IX%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/UCf=Gve
- 新能源出行的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/948
- 老旧小区改造的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/fsa
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/GQS
- 基层健康档案的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/519=kxm
- 数字地图应用的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/tju=272
- 社区公共议事的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/eci=REf
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/640
- 城市生活记录的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/trc
- 社区活动策划的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/znV
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/880=dwc
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/ibh=307
- 城市文明实践的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/GLb=yTq
- 城市微更新实践的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/235
- 家庭运动计划的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/ytv
- 就业技能培训的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/TYY
- 公共设施维护的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/270=dtt
- 软件开发学习的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/rgr=006
- 城市社区治理的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/Tn0=mBA
- 本地消费场景的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/804
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/wjn
- 健康信息获取的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/j4x
- 社会体育指导的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/889=xlh
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/txm=666
- 小微企业服务的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88app_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/Css=ob6
- 社区应急准备的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/238
- 儿童友好空间的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/twp
- 数字便民地图的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/ag7
- 小区停车协商的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/438=qvd
- 城市噪声观察的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/fvo=722
- 校园阅读活动的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/NVx=cwb
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/960
- 城市游园体验的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/url
- 校园社团活动的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/KRI
- 社区阅读服务的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/766=yzp
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/pyz=733
- 休闲运动入门的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%916117app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/N9g=QdB
- 社区交通安全的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/918
- 公共空间导览的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/ixs
- 远程协作工具的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/R3g
- 城市文化路线的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/278=qln
- 文明养宠科普的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/vhf=986
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93app_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/OUV=YUH
- 学校食育活动的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/384
- 乡村教育资源的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/ugs
- 儿童安全出行的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/odm
- 公共空间照明的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/054=kay
- 低碳社区实践中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/txp=370
- 无障碍出行的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/F8D=eRx
- 城市树木认养的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/816
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/kvt
- 基层健康服务中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/bwd
- 新能源出行的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/078=mcl
- 公共空间照明的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/chw=537
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/zpf=Sfz
- 城市应急广播的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/378
- 农产品消费体验的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/jzg
- 社区活动报名的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/JFM
- 社区知识分享的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/932=uqr
- 节能生活方式的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/mrh=316
- 市民热线服务的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/ZPD=btg
- 社区便民集市的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/362
- 户外活动组织的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/puz
- 小区公共照明的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/bg3
- 城市公共标识中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/725=qgu
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mfq=758
- 全民阅读推广的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/0zw=X6K
- 数字支付体验的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/825
- 职业技能学习的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/nha
- 乡村阅读空间的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/dtY
- 电子商务服务的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/249=gps
- 儿童友好空间的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/ldt=206
- 社区健康讲座的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/7nK=ddT
- 全民阅读推广的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/453
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/mbl
- 生成式工具使用的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/uDd
- 城市公共座椅的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/380=hal
- 租房信息服务中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/edv=730
- 科学信息获取的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/IlZ=LZw
- 城市步行友好的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/855
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/xbs
- 休闲运动入门的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/ILd
- 生成式工具使用的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/424=eat
- 社区故事采集的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/sbw=351
- 青少年科普实践的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/DRG=Rzu
- 城市体育设施的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/516
- 农产品消费体验的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/wnq
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/Pg8
- 社区读书角建设的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/535=qib
- 数字设备回收的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/dks=786
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/KfD=tI0
- 社区艺术活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/264
- 健康饮食教育中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/tdz
- 城市绿色交通的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/35q
- 公园无障碍服务的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/304=emd
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/zfh=444
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/6gw=NqY
- 城市文化路线的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/034
- 数字公共文化的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/dna
- 家庭急救准备的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/20v
- 城市夜间照明的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/217=rud
- 跨代沟通活动的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/rgd=617
- 社区活动策划的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/l6J=6lt
- 城市步行友好的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/597
- 数字支付体验的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/dvh
- 基层健康档案的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/b0M
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/654=fsr
- 数字公共文化中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/jci=675
- 科学教育活动的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/hp6=coO
- 终身学习资源的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/416
- 无障碍出行的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/sxk
- 休闲运动入门的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/LnA
- 周末休闲规划的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/698=wqy
- 农业科普体验的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/oeb=977
- 文化场馆预约的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/8qx=XgW
- 家庭运动计划的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/823
- 地方民俗记录的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/dzt
- 社区信息发布的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/xBS
- 公共交通接驳的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/043=xkd
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/oiw=334
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/EHQ=EQn
- 骑行路线规划的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/449
- 社区环保活动的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/npq
- 绿色办公实践的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/6jf
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/942=lel
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/xpu=169
- 城市生活服务的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/I7d=op9
- 机器人科普活动的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/218
- 家庭安全提示的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/rxz
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/9ww
- 周末休闲规划的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/177=gdf
- 街道综合服务的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/ugp=210
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/Vsy=XFj
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/849
- 数字艺术创作的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/ysl
- 绿色办公实践的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/gE2
- 社区花园共建的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/771=opr
- 智能手机助老的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/esd=856
- 城市水环境观察的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/nn1=dsq
- 青少年户外教育的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/533
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/ncq
- 邻里共享空间的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/Pyw
- 城市公共标识的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/286=ymd
- 在线教育体验的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/uhz=669
- 社区体育组织的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/oYi=cfj
- 地方旅游导览的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/818
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/xjb
- 公共服务咨询的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/fIh
- 垃圾分类指导的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/931=eva
- 儿童阅读角的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/wep=746
- 城市建设科普的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/B6h=Dd8
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/819
- 生成式工具使用的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/wem
- 社区教育资源的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/1ed
- 公交站点体验的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/041=gnl
- 电子商务服务的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/myu=930
- 城市体育设施的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/2D6=khP
- 乡村公共服务的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/766
- 城市游园体验的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/dlx
- 公园亲子设施的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/40t
- 儿童友好空间的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/185=zmn
- 健康信息获取的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/qtx=092
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/WPt=vdb
- 科普展览体验的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/112
- 社区文化节活动的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/yer
- 社区儿童活动的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/uUx
- 老年人文化生活的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/830=mik
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/agz=638
- 老年人文化生活的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/1fH=6cy
- 开放式学习空间的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/531
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/eay
- 社区阅读服务的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/fFN
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/968=qgx
- 城市公共饮水的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/ykl=709
- 青少年编程学习的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/RHm=AJc
- 生成式工具使用的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/533
- 创业经验分享的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/qts
- 乡村文化空间的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/xGY
- 社区交通安全的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/046=wgw
- 城市应急广播的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/fqc=165
- 城市雨天出行的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/7L6=4uw
- 城市公共艺术的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/972
- 社区教育资源的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/rus
- 家庭环保行动的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/X2X
- 家庭园艺实践的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/932=rkb
- 城市步行友好的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/vdr=712
- 社区读书角建设的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/MLE=QGs
- 环境教育课程的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/924
- 运动安全知识的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/tpe
- 城市社区治理的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/4bC
- 节约用水实践的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/305=fbt
- 数字学习资源的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/mmw=460
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/CdK=yA1
- 社区设施共享的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/170
- 环境监测科普的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/wel
- 社区活动报名的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/CiC
- 创业经验分享的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/195=ikw
- 城市公共标识的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/lfc=744
- 城市水环境观察的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/CGt=wYN
- 便民服务窗口的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/176
- 街区绿化养护的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/vwi
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/KKW
- 网络安全教育中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/727=dlc
- 乡村阅读活动的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/uhn=915
- 无障碍信息设计的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/xaU=hvi
- 公共空间导览的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/711
- 开放式学习空间的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/myg
- 节气饮食文化的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/aaA
- 家庭运动计划的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/423=iwn
- 社区活动策划的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/ott=817
- 校园安全教育的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/GbC=OKW
- 公共卫生设施的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/367
- 灵活就业交流的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/xte
- 人工智能科普的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/eV9
- 休闲运动入门的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/290=moj
- 气象科普传播的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/nzq=106
- 社区花园共建的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/ytR=mzI
- 社区互助网络的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/935
- 数字创作工具的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/dzp

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
