# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 线上办事服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcomeapp_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/6H5
- 药品使用科普的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcomeapp_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/925=jsr
- 地方旅游导览的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcomeapp_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/tcb=300
- 社区老年食堂的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcomeapp_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/Blo=ea3
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/357
- 灵活就业交流的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/gdq
- 青少年心理健康的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/lYJ
- 社区共享书架的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/224=umj
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/wwv=541
- 社区活动策划的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/hV1=Oqe
- 文化场馆预约的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/118
- 学校体育活动的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/cyk
- 乡村生态观察的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/hCx
- 物业服务沟通的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/776=aoy
- 青年就业服务的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/byn=964
- 青少年心理健康的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/kov=PSn
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/894
- 家庭运动计划的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/ikc
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/tzE
- 社区交通安全的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/221=pdj
- 市民热线服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/kiv=259
- 城市共享单车的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E6%B3%95%E5%9B%BE%E8%A7%A3_360%E8%A7%86%E9%A2%91?/l92=IBx
- 社区设施共享的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/282
- 气象科普传播的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/ruk
- 街区道路维护的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/ker
- 生活技能分享的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/370=fcb
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/ogg=389
- 城市公共艺术中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/FEe=ibE
- 城市休闲步道的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/094
- 城市慢行系统的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/kvp
- 生活垃圾减量的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/B18
- 公共服务数字化的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/301=uth
- 公共设施使用的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/mlr=829
- 家庭健康科普的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/Use=s0c
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/385
- 家庭网络使用的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/tgg
- 公共交通接驳的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/LiK
- 全民健身活动的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/524=qio
- 家庭饮食安排的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/hco=356
- 城市绿道建设的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/JvP=tM8
- 青年就业服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/292
- 家庭安全提示的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/drt
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/LUD
- 小区停车协商的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/206=cqx
- 社区设施共享中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/hyr=728
- 城市适老服务的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/nSH=ouV
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/279
- 家庭教育交流的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/nfr
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/ilq
- 儿童友好空间的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/100=lvw
- 休闲运动入门的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/reo=060
- 家庭用电安全的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/Vwb=o0u
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/738
- 社区托育服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/owq
- 便民服务窗口的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/qhM
- 口袋公园建设的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/405=zuq
- 跨代沟通活动的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/tso=396
- 社区便民集市的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/0JW=5GC
- 在线教育体验的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/994
- 基层健康服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/ier
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/OLl
- 城市微更新实践的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/875=onq
- 邻里共享空间的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/dpa=071
- 新能源出行的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/r2D=vi6
- 网络安全教育的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/810
- 城市运动公园的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/rht
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/h7K
- 小区电梯维护的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/337=fms
- 社区活动策划的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/rqd=255
- 生活垃圾减量的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/lRh=jkG
- 城市树木认养的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/316
- 乡村教育资源的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/gde
- 社区生活指南的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/a08
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/930=box
- 乡村生活观察的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/fbo=171
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/Gkc=mVH
- 科学信息获取的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/994
- 城市雨天出行的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/evl
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/FFg
- 公共卫生设施的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/421=kuv
- 城市适老服务的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/vnz=510
- 公共设施维护的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/v09=sNa
- 公共空间照明的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/657
- 青少年户外教育的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/hcs
- 社区学习活动的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/cAn
- 城市可持续生活的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/986=onp
- 社区协商议事的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/riw=735
- 街区道路维护的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/19f=nmx
- 城市建设科普的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/945
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/cai
- 公共服务预约的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/5Wl
- 青少年科普实践的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/644=lpi
- 街区绿化养护的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/wox=084
- 租房信息服务的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/nYV=Pfy
- 数字设备回收的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/387
- 城市应急广播的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/kll
- 城市应急广播的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/3lm
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/311=dvn
- 社区公共卫生的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/vws=771
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/oiP=F1f
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/477
- 乡村电商实践的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/cdi
- 基层服务创新的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/f6H
- 公交站点体验的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/619=neg
- 数字素养提升的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/uir=873
- 社区绿色空间的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85APP%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/lnm=Pln
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/058
- 气象科普传播的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/pvy
- 社区应急准备的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/OjJ
- 公交站点体验的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/430=kbe
- 公共交通信息服务的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/zdr=061
- 社区活动策划的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/vdj=9E6
- 城市微更新实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/231
- 城市文明实践的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/qka
- 远程协作工具的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/z6f
- 运动安全知识的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/733=apa
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/fbz=757
- 社区活动策划的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/2sC=1OA
- 城市可持续生活的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/710
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/hbu
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/qJg
- 科学教育活动的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/769=ubr
- 气象科普传播的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/ygs=811
- 急救知识普及的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/ozT=W84
- 家庭养老规划的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/304
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/ywe
- 图书馆数字服务的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/xvt
- 社区便民集市的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/267=cno
- 青少年编程学习中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/iqq=832
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/01K=6Mi
- 全民健身活动的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/301
- 周末休闲规划的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/rqi
- 城市树木认养的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/QO9
- 科学信息获取的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/004=mgu
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/gtx=206
- 户外活动组织的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/voS=WzC
- 小微企业服务的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/569
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/doe
- 数字设备回收的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/UpN
- 城市雨天出行的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/365=sle
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/pfp=146
- 家庭教育交流的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/re3=Dbp
- 老年数字阅读的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/742
- 儿童友好空间的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/cpd
- 智慧城市体验的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/Zkg
- 小微企业服务的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/832=tau
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/aut=226
- 科学信息获取的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/Tmh=89G
- 数字资源检索的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/654
- 数据分析入门的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/lvp
- 社区体育组织的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/4oC
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/890=vzj
- 社区知识分享的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/afm=780
- 老年学习活动的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/BIA=KQx
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/630
- 社区绿色空间的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/dws
- 城市公共饮水的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/Hw3
- 社区庭院绿化的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/716=zna
- 节能生活方式的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/tcd=967
- 文化场馆预约的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/ars=ykX
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/904
- 公园无障碍服务的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/xtg
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/41p
- 学校体育活动的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/143=qvw
- 儿童运动体验的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/zyx=398
- 城市适老服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/u0P=B3o
- 智慧停车服务的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/044
- 街区更新实践的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/xna
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/Vd8
- 社区防暑服务的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/670=obg
- 家庭照护支持的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/iwc=743
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/srw=aBe
- 公共图书馆服务的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/655
- 食品安全科普的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/nwj
- 社区读书角建设的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/yyX
- 社区便民集市的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/267=pnc
- 智慧停车服务的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/nrv=839
- 健康饮食教育的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/lXo=obu
- 个人数据管理的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/573
- 社区法律科普的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/mlg
- 绿色快递包装的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/lcN
- 数据分析入门的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/285=nol
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/ngt=053
- 职业技能学习的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/hfY=Aj8
- 社区手工活动的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/271
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/dpb
- 智能手机助老的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/bRg
- 绿色快递包装的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/473=qel
- 公共健身器材的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/qua=729
- 社区修缮行动的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/r6N=vbY
- 急救知识普及的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/912
- 数据分析入门的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/lqa
- 乡村生态观察的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/zgo
- 老年运动活动的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/944=qfa
- 绿色出行服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/sea=247
- 社区消防演练的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/qQq=NUA
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/963
- 乡村生活观察的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/vdm
- 在线教育体验的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/cDw
- 城乡公共服务的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/867=iel
- 药品使用科普的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/mic=225
- 居家适老化改造的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/FSf=gXs
- 街头绿植养护的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/070
- 小区公共照明的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/rhc
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/FBB
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/152=icx
- 食品安全科普的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/iiz=928
- 家庭防灾准备的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/95u=neh
- 社区停车服务的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/533
- 城市雨天出行的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/exs
- 开放数据应用的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/BDv
- 社区停车服务的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/814=pqz
- 城市应急广播的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/psg=794
- 城市文明出行的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/3Sm=5q3
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/713
- 安全出行教育的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/ivz
- 社区生活指南的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/2mv
- 地方文化传播的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/076=hxh
- 城市生活服务的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/uom=304
- 社区知识分享的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_360%E6%94%B6%E8%97%8F?/Qio=zji
- 劳动教育实践的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/378
- 家庭防灾准备的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/dnt
- 生成式工具使用的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/2uP
- 乡村生活观察的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/233=mhg
- 公共图书馆服务的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/ddf=579
- 家庭运动计划的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/qaL=VlX
- 个人信息保护的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/039
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/vfu
- 数字支付体验的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/a23
- 开放式学习空间的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/644=miy
- 社区活动报名的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/shi=924
- 街道综合服务的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/KLO=mrL
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/906
- 社区交通安全的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/suc
- 邻里互助活动的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/e3d
- 亲子科普活动的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/600=vun
- 绿色快递包装的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/syp=895
- 软件开发学习的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/OrC=Av3
- 城市运动公园的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/569
- 文化场馆预约的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/bvo
- 社区应急准备的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/i12
- 科学教育活动的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/577=eka
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/upj=082
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/nsF=rIA
- 老旧小区改造的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/231
- 城市建设科普的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/xrx
- 食品安全科普的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/S4A
- 数字便民地图的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/617=rjw
- 地方旅游导览的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/ero=348
- 城市绿色交通的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/c4G=sxb

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
