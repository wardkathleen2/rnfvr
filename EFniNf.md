# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:22**

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

- 科学运动指导从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/ooa=856
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/35K=LIG
- 数字政务体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/835
- 城市文明实践的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/cfv
- 城市公共艺术的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/M97
- 数字档案服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/836=btm
- 社区环保活动的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/ykd=853
- 城市体育设施的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/mUU=TBl
- 公交站点体验的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/063
- 人工智能科普的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/axh
- 家庭收纳实践的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/Bs4
- 地方戏曲体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/551=jhb
- 城市生活记录的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/mnu=914
- 电子商务服务的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/m81=TsK
- 城市基础设施的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/298
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/gsu
- 农业科普体验的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/zeI
- 社区法律科普的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/141=lju
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/gzt=934
- 公共设施维护的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/LFT=XN9
- 智能手机助老的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/554
- 社区环保活动的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/erw
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/4d2
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/342=vvo
- 线上办事服务的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/ywq=952
- 生活技能分享的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/8dI=r83
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/168
- 环境教育课程的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/gjq
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/rLn
- 城市公共自行车的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/469=nov
- 城市基础设施的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/ewd=002
- 社区互助网络的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/IlO=Ql6
- 本地历史资料的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/923
- 社区体育组织的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/xfw
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/rrM
- 城市步行环境的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/895=ake
- 学校食育活动的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/kej=050
- 青少年编程学习的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/pdU=cJZ
- 城市公共自行车的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/000
- 城市文明实践中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/nut
- 社区知识分享的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/I9I
- 城市建设科普的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/150=rox
- 公交无障碍服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/vyr=787
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/tCG=2yI
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/425
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/ogl
- 校园社团活动的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/Zxo
- 乡村生活观察的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/095=ace
- 城市文明实践的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/ybn=438
- 科学信息获取的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/ZFe=pag
- 生活技能分享的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/761
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/ezs
- 居民健康教育的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/0Ck
- 城市住房服务的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/871=cdt
- 城市展览体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/wam=281
- 社区信息发布的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/xAS=hi5
- 社区修缮行动的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/779
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/stk
- 社区活动策划的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/CHR
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/145=oml
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/kqk=228
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/PMz=4u4
- 绿色校园实践的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/203
- 户外活动组织的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/vby
- 家庭环保行动的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/H6Z
- 城市树木认养的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/404=bho
- 社区商业活力的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/aqh=015
- 消防知识宣传的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/Zoq=PdL
- 城市文明实践的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/685
- 社区协商议事的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/qsb
- 课后服务体验的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/OeZ
- 智慧停车服务的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/284=vck
- 数字支付体验的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/jrj=122
- 城市运动公园的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/vBM=d5A
- 青少年编程学习的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/952
- 信息无障碍体验的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/bfc
- 家庭健康管理的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/oOq
- 城市农夫市集的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/493=egj
- 文化讲座服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/unb=640
- 城市地名文化的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/7js=4cC
- 城乡交通衔接的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/194
- 社区阅读服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/vyi
- 城市雨天出行的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/rOW
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/022=qfy
- 绿色出行服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/vuo=575
- 个人时间管理的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/bsb=yVB
- 口袋公园建设的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/695
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/pfc
- 社区手工活动的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/rl4
- 公共空间照明中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/066=urg
- 城市游园体验的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/qga=877
- 街区更新实践的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/Kmx=s2M
- 城市骑行环境的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/540
- 社区宠物管理的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/lgh
- 网络信息辨识的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/ah6
- 家庭安全提示的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/751=rtm
- 社区生活指南的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/sjc=594
- 公共交通接驳的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/ozt=gyE
- 老年友好服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/657
- 公共服务数字化的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/jmg
- 家庭收纳实践的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/Qq1
- 文化讲座服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/561=jde
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/taj=991
- 乡村生态观察的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/kuJ=byS
- 急救知识普及的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/326
- 社区志愿服务的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/oiw
- 城市运动公园的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/B9Q
- 公共服务咨询的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/779=dck
- 乡村公共服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/lja=756
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E8%99%8E%E6%89%91%E5%A8%B1%E4%B9%90?/s8N=4t0
- 社区科普课堂的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/955
- 城市文化路线的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/zxw
- 电动汽车充电的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/NBa
- 校园节能行动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/353=suv
- 社区故事采集的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/agw=708
- 社区公共卫生中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/OwZ=AYz
- 基层医疗预约的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/340
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/qmv
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/Tw2
- 便民维修服务的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/533=ano
- 青年职业探索的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/iys=505
- 个人信息保护中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/77j=TVO
- 数字资源检索的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/727
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/anw
- 社区便利生活的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/Viy
- 节日文化体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/659=uws
- 街区绿化养护的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/hix=751
- 老年人日常照护的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/mxB=7bO
- 城市体育设施的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/069
- 休闲运动入门的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/wkg
- 光伏知识科普的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/FmG
- 学校体育活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/485=cjg
- 公园休闲体验的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/jqt=489
- 低碳社区实践的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/ZQE=lKU
- 城市公共艺术的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/935
- 数字学习资源的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/sbi
- 公共服务评价中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/v1c
- 公共空间导览的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/194=amd
- 地方戏曲体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/mwi=089
- 乡村阅读活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/Sew=UkM
- 地方旅游导览中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/380
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/zsi
- 职业技能学习的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/Kde
- 读书会组织的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/943=gsp
- 社会体育指导的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/iql=086
- 社区教育资源的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/Pfx=I4d
- 网络安全教育的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/702
- 公共交通接驳的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/bwi
- 乡村公共服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/b4O
- 小区停车协商的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/638=iuc
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/lgc=714
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/cgN=a9Z
- 农村环境治理的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/489
- 城市微更新实践的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/akc
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/luo
- 公园亲子设施的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/710=ych
- 学校食育活动的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/zdt=629
- 生活垃圾回收的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/Azx=lHY
- 电动汽车充电的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/006
- 乡村教育资源的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/lqk
- 公共空间照明的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/zeM
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/367=ltc
- 图书借阅体验的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/xcf=140
- 运动安全知识的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/uBI=9RL
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/163
- 社会体育指导的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/gbz
- 电动汽车充电的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/z5z
- 终身学习资源的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/691=zfa
- 家庭收纳实践的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/cvt=845
- 绿色快递包装的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/Yal=tvg
- 儿童户外活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/545
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/vhb
- 志愿服务平台的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/fLL
- 城市夜间生活的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/263=qas
- 基层服务创新的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/pjq=239
- 城市文明实践的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/Afq=a0d
- 社区信息发布的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/992
- 城市应急广播的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/mxr
- 城市步行环境的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/Qgx
- 老年人文化生活的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/725=fxe
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/kbz=303
- 社区绿色空间的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/3aF=B2o
- 城市公共自行车的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/344
- 家庭环保行动的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/kcl
- 便民维修服务的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/7kS
- 健康饮水科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/752=ovi
- 社区快递服务的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/yqg=882
- 开放数据应用的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/Bhf=8Oj
- 城市建设科普的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/474
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/jhy
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/CQf
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/734=ihj
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/hua=274
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/6l9=xvN
- 社区法律科普的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/889
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/qle
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/gb7
- 社区志愿服务的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/904=mdu
- 家庭教育交流的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/syk=915
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/ciB=0Rr
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/913
- 社区知识分享的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/rvb
- 城乡交流活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/sEw
- 科学教育活动的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/323=ytl
- 职业技能学习的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/cyq=804
- 基层医疗预约的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/03t=dKh
- 社区艺术活动的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/925
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/fhb
- 公益活动组织的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/EIF
- 智慧城市体验的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/563=omu
- 绿色办公实践的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/tbz=908
- 基层健康档案的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/JPb=GA9
- 社区交通安全的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/038
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kps
- 校园节能行动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/OsP
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/983=ryz
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/loz=604
- 文化场馆预约的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/8M4=RXY
- 街区更新实践的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/080
- 公共服务评价的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/oqp
- 家庭网络使用的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/qaZ
- 便民维修服务的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/236=qjz
- 农贸市场环境的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/bbr=166
- 环境教育课程的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/E3e=AWM
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/591
- 骑行路线规划的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/uah
- 公共场所导视的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/7cO
- 乡村教育资源的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/481=nmp
- 老年友好服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/wfd=367
- 校园社团活动的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/VYO=oCU
- 公共服务咨询的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/262
- 农产品消费体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ixm
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Vni
- 城市体育设施的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/068=weo
- 城市应急广播的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gth=866
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lv4=pTG
- 节能家电使用的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/771
- 地方美食文化的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/ufu
- 家庭志愿活动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/x4O
- 网络安全教育的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/024=cjv
- 社区协商议事的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/upl=079
- 公交站点体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/2hk=aGP
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/762
- 老年学习活动的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/sdh
- 社区阅读服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/p58
- 城市适老服务的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/204=yzu
- 健康饮水科普的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/wrv=569
- 新能源出行的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/D7k=5q2
- 街道综合服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/232
- 亲子科普活动的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/jyg

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
