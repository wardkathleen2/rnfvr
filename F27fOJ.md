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

- 开放式学习空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_360%E7%95%85%E6%B8%B8?/tg7
- 周末休闲规划的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_360%E7%95%85%E6%B8%B8?/585=olf
- 健康步道使用的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_360%E7%95%85%E6%B8%B8?/rmb=925
- 儿童友好空间的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_360%E7%95%85%E6%B8%B8?/xXt=hSf
- 社区健康讲座中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/863
- 社区便民服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/wxh
- 本地历史资料的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/UsK
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/273=sre
- 老年智能设备的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/hdh=234
- 绿色办公实践的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/ZVE=aT7
- 城市体育设施的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/352
- 农产品品牌传播的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/rjx
- 节能生活方式的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/UuN
- 公共服务预约的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/090=nvh
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/vzj=985
- 公共设施维护的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/fMV=8hY
- 网络安全教育的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/310
- 邻里互助活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/wus
- 图书借阅体验的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/Lrk
- 社区便利生活的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/097=vwe
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/udb=643
- 社区法律科普的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91pgapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/PMg=C0g
- 城市步行友好的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/107
- 城市公共艺术的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ecl
- 家庭照护支持的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/PDl
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/033=hhb
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/uac=227
- 城市共享单车的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BDapp_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/xfh=X6N
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/217
- 生成式工具使用中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/dyd
- 乡村公共服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/YrO
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/449=udf
- 青年职业探索的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/alt=130
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/QKQ=K55
- 生活垃圾回收的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/694
- 城市公共座椅的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/xrj
- 图书借阅体验的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/2WK
- 校园阅读活动的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/220=bqu
- 老年运动活动的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/jxn=781
- 社区消防演练的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/jvZ=h1n
- 家庭环保行动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/928
- 青年志愿活动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/rkv
- 城市住房服务的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/0LM
- 社区知识分享的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/918=dhu
- 数字档案服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/ajj=193
- 街区绿化养护的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770www_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/a85=Vow
- 校园安全教育的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/963
- 口袋公园建设的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/auh
- 节能家电使用的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/40U
- 城市农夫市集的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/291=prh
- 家庭消费规划的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/xkx=636
- 课后服务体验的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/TwJ=zS1
- 社区商业活力的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/541
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/vpz
- 公共设施维护的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/fC9
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/799=wkx
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/uwe=373
- 文化场馆预约的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/i7v=Sdp
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/648
- 旧物循环利用的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wyh
- 社区老年食堂的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/PBT
- 家庭节能实践的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/978=tjk
- 社区公共卫生的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/vst=229
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/RrK=Vq7
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/263
- 社区休闲设施的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/vko
- 社区科普课堂的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/ooI
- 校园节能行动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/405=cik
- 社区公共议事的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/mvl=927
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/JKr=E8Q
- 全民健身活动的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/799
- 科学教育活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/sbv
- 家庭运动计划的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/SEs
- 地方旅游导览的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/805=xst
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/lhx=898
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/PH0=YGv
- 城市运动公园的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/731
- 城乡公共服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/jfw
- 药品使用科普的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/xBX
- 本地旅行体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/427=ppp
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/xuj=190
- 青年就业服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/Q0D=oII
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/909
- 开放数据应用的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/ong
- 家庭科学教育的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/aG5
- 光伏知识科普的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/494=kkr
- 城市公共厕所的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/avv=476
- 社区便民服务的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/79s=lfz
- 社区公共卫生的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/704
- 节假日出行安排的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/fmt
- 校园阅读活动的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/kzz
- 通勤路线规划的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/217=ibw
- 城市微更新实践的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/bhk=857
- 灵活就业交流的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91app_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/mhh=uu3
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/946
- 居家适老化改造的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/lae
- 乡村公共阅读的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/bFE
- 城市可持续生活的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/330=ocg
- 市民热线服务的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/itl=094
- 文化讲座服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E9%97%AE%E5%8D%B7?/39Z=saI
- 本地旅行体验的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/221
- 便民服务窗口的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/fci
- 农贸市场环境的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/PgN
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/362=fak
- 通勤路线规划的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/wpw=759
- 社区文化节活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/Y4D=Eub
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/469
- 电动汽车充电的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/htz
- 劳动教育实践的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/OXx
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/819=izo
- 城市噪声观察的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/kax=111
- 儿童安全出行的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/cDY=pp5
- 青年就业服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/986
- 家庭健康管理的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/ddn
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/5yL
- 灵活就业交流的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/187=nyh
- 劳动教育实践的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/mae=729
- 社区知识分享的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/w1E=MSL
- 校园社团活动的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/792
- 软件开发学习的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/mjv
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/pvR
- 开放式学习空间的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/178=eoc
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/sys=088
- 街区道路维护的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/a2Y=VNa
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/820
- 城市便民驿站的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/oes
- 街区更新实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/njV
- 公共服务咨询的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/253=fkt
- 城市游园体验的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/ibl=311
- 公共图书馆服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/wuz=cyM
- 公共服务数字化中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/381
- 公交站点体验的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/qxj
- 老年人日常照护的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/Xr8
- 学校体育活动的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/410=syu
- 城市文明实践的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/rjc=868
- 家庭急救准备的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BDapp_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/1gv=4Hg
- 社区活动策划的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/343
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/bzy
- 社区故事采集的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/Zji
- 物业服务沟通的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/072=dpd
- 日常摄影记录的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/wad=269
- 街区绿化养护的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/V4y=dVJ
- 城市生活记录的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/365
- 开放式学习空间的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/qob
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/ar0
- 公共服务评价的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/834=plb
- 租房信息服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/oih=063
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/hAW=b5B
- 通勤路线规划的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/202
- 家庭收纳实践的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/dpv
- 社区设施共享的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/Ur8
- 生活服务数字化的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/393=ykm
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/jwt=163
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/PDU=Ob2
- 乡村公共文化的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/406
- 本地旅行体验的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/lra
- 城市博物馆服务的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/L93
- 图书借阅体验的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/840=krm
- 科技馆参观体验的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/npw=765
- 数字课堂应用的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/ony=U56
- 街头绿植养护的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/955
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/uoj
- 公共文化活动的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/38c
- 家庭节能设备的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/829=ngp
- 城市休闲步道的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/dbc=758
- 个人信息保护的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/XZ0=ko2
- 租房信息服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/834
- 社区活动策划的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/vid
- 公共卫生设施的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/q58
- 小区公共照明的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/107=mef
- 居家防滑改造的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/mbz=630
- 城市公共自行车的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/CEw=Oe9
- 社区便民集市的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/170
- 节能生活方式的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/gay
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/Dzt
- 公共空间照明的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/757=ana
- 旧物循环利用的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/dgf=462
- 城市雨天出行的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/R7T=LTz
- 城市公共艺术的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/894
- 非遗课堂体验的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/rda
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/nKq
- 社区运动空间的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/535=ddz
- 食品安全科普的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/jqn=317
- 学校体育活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%A2_360%E6%B8%AF%E8%82%A1?/kiV=ovK
- 社区活动空间的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/244
- 城市树木认养的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/bpi
- 城市微更新实践的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/tSE
- 地方文化传播的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/987=csy
- 社区停车服务的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/ixu=623
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%91%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/QdB=oBb
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/108
- 小微企业服务的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/szx
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/ORd
- 数字便民地图的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/788=cvh
- 校园安全教育的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/hdz=340
- 运动安全知识中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/OKG=Zdk
- 家庭用电安全的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/028
- 城市展览体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/lug
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/vZ1
- 社区共享书架的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/193=gzj
- 开源技术交流的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/jmu=194
- 社区垃圾分类的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/x4n=RVk
- 节日文化体验的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/226
- 校园社团活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/vxb
- 城市博物馆活动的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/HB5
- 个人时间管理的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/157=ktu
- 公园休闲体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/xxd=526
- 社区托育服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/PSN=DJH
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/044
- 城市文明实践的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/suf
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/Jmm
- 社区便民服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/252=qxr
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/mmc=704
- 小区电梯维护的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/9iq=0sN
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/338
- 小微企业服务的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/dzl
- 城市公共座椅中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/9Z4
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/608=zhn
- 社区家校合作的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/fag=856
- 新能源出行的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/JQi=Qnw
- 社区学习活动的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/723
- 个人数据管理的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/xkt
- 公共空间导览的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/B64
- 电子商务服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/234=qfw
- 便民服务地图的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/cfa=796
- 志愿者培训交流的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/t2n=C82
- 青年职业探索的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/118
- 通勤路线规划的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/ava
- 社区垃圾回收的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/8gC
- 城市基础设施的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/563=jag
- 骑行路线规划的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/lwj=849
- 地方旅游导览的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/P4X=DQ7
- 社区交通安全的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/789
- 文化讲座服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/bvo
- 社区托育服务的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/kY6
- 社区法律科普的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/842=xnw
- 社区快递服务的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/bli=388
- 节假日出行安排的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/NOd=P3o
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/194
- 家庭科学教育的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/dvn
- 老年人日常照护的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/EJl
- 城市共享单车的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/244=mnv
- 家庭理财科普的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/imy=911
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/P57=u0c
- 城市雨天出行的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/657
- 个人时间管理的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/nmn
- 城市应急科普的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/MNC
- 公共卫生宣传的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/672=oev
- 在线学习体验的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/dsa=249
- 公共交通接驳的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/gLY=caK

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
