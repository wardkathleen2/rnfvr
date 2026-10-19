# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:16**

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

- 社区花园共建的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/ove=356
- 家庭收纳实践的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/w6l=9No
- 节假日出行安排中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/688
- 农村环境治理的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/ddn
- 城市生活服务的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/iJ2
- 城乡交流活动的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/537=viy
- 城市夜间生活的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/myt=177
- 公共场所导视的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/9C1=ibP
- 数字便民地图的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/523
- 社区便利生活的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/vij
- 社区便利生活中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/hkP
- 农产品消费体验的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/815=bjm
- 城市游园体验的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/efr=959
- 电子商务服务中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/PrR=2mm
- 乡村生态观察的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/930
- 基层健康服务的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/zjx
- 全民健身活动的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/7hd
- 公共服务指南的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/515=tce
- 老年智能设备的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/iwj=817
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/5S2=k5i
- 城市适老服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/833
- 运动安全知识的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/fqk
- 乡村公共服务的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/TFC
- 家庭节能设备的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/481=lbb
- 社区学习活动的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/hyi=603
- 城市空气科普的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/QsE=OdP
- 开源技术交流的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/960
- 社区环保活动的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/krx
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/Tb4
- 便民服务窗口的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/659=wjz
- 生活技能分享的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/hct=370
- 地方旅游导览的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/IhO=eKn
- 老年友好服务的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/714
- 社区文化节活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/ess
- 城市文明出行的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/ODn
- 城市公共自行车的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/022=iwm
- 家庭收纳实践的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/vag=607
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/wW1=MU1
- 农业科普体验的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/071
- 便民维修服务的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/zlp
- 家庭环保习惯的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/TzQ
- 基层健康服务的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/789=uvf
- 公共场馆服务的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/pih=905
- 街区绿化养护的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/Itv=rXP
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/512
- 网络信息辨识的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/ztk
- 数字支付体验中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/Fpc
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/357=cvj
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/gib=488
- 基层健康档案的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/NF1=as7
- 居家适老化改造的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/577
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/nof
- 社区共享书架的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/CDW
- 线上阅读资源的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/363=bqt
- 志愿服务平台的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/adm=247
- 绿色生活实践的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/2RQ=nFw
- 在线学习体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/959
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/vlv
- 急救知识普及的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/uez
- 乡村公共文化的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/334=azz
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/usv=423
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/ofi=q5o
- 家庭园艺实践的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/342
- 城市建设科普的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/jgs
- 基层健康档案的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/ns8
- 科普展览体验的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/559=zoo
- 社区知识分享的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/nph=816
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/lkt=QpY
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/764
- 口袋公园建设的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/zfd
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Ny0
- 社区信息发布的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/184=qwu
- 青少年心理健康的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pmj=053
- 小区电梯维护的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/4pf=HNy
- 社区设施共享的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/906
- 城市骑行环境的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/vej
- 社区便民集市的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/oEs
- 社区环保活动的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/722=zmp
- 智慧停车服务的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/wib=730
- 图书馆数字服务的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/q70=GTx
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/996
- 科学健身方法的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/vjv
- 城市噪声观察的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/314
- 家庭消费规划的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/476=dkf
- 城市绿色交通的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/jju=621
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/p1W=CC5
- 地方旅游导览的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/941
- 社区停车服务的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/okk
- 食品配送体验的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/BBM
- 数字阅读服务的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/817=ycn
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/xon=699
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/jBq=t5f
- 电子商务服务的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/873
- 食品配送体验的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/qma
- 公共服务咨询的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/Xqb
- 骑行路线规划的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/474=ggt
- 社区老年食堂的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/lcs=860
- 绿色生活实践的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/vmX=4Yb
- 全民健身活动的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/820
- 课后服务体验的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/byr
- 城市步行环境的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/ZHe
- 街区绿化养护中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/843=gug
- 科技馆参观体验的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/zzd=131
- 健康信息获取的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/E6i=DwU
- 小微企业服务的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/302
- 小区公共照明的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/tab
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/VMb
- 在线学习体验的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/782=qyr
- 医院导诊服务的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/hpj=853
- 就业技能培训的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/BCi=6lF
- 数字课堂应用中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/784
- 校园节能行动的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/btz
- 城市建设科普的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/lG5
- 城市雨天出行的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/551=pmr
- 数字创作工具的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/rdn=578
- 公共设施使用的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/YYN=tEZ
- 城市公共饮水的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/213
- 本地历史资料的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/skz
- 城市共享单车的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/GAc
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/323=ifq
- 城市公共饮水的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/qap=269
- 公共服务预约的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/YiV=Dvn
- 运动安全知识的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/315
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/ytz
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/0Nh
- 电子商务服务的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/278=osk
- 科学健身方法的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/dol=050
- 城乡公共服务的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/Ttq=vzs
- 家庭照护支持的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/617
- 个人时间管理的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/zdv
- 家庭急救准备的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/uL0
- 无障碍出行的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/471=zpo
- 生成式工具使用的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/tjm=773
- 农村环境治理的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/Q0O=IVl
- 急救知识普及的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/491
- 家庭理财科普的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/yyp
- 节假日出行安排的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/tM5
- 消防知识宣传的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/934=hut
- 社区生活指南的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/nwe=160
- 公共空间照明的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/eHL=3QG
- 社区防暑服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/107
- 公共文化活动的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/evh
- 绿色出行服务的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/P0z
- 非遗体验活动的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/630=mji
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/inj=807
- 校园节能行动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/L53=WKh
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/478
- 开放式学习空间的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/ifv
- 城市适老服务的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/2Qt
- 城市空气科普的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/769=kaq
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/hxo=610
- 本地消费场景的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/HRh=Bf2
- 学校食育活动的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/193
- 青年职业探索的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/mji
- 电动汽车充电的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/1kF
- 公共服务沟通的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/041=tht
- 基层医疗预约的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/lse=177
- 社区养老服务的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/kZS=MPU
- 城市水环境观察的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/463
- 数字生活课堂的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/til
- 光伏知识科普的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/VBA
- 气象科普传播的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/594=fmc
- 城市步行友好的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/xyu=121
- 校园社团活动的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/PZv=IzX
- 数字便民地图的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/366
- 社区邻里服务的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/tdf
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/j4n
- 数字创意课程的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/357=mbw
- 课后服务体验的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/gqg=720
- 生活服务数字化的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/kjn=YRz
- 城市绿道建设的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/023
- 无障碍信息设计的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/imx
- 社区公共餐饮的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/tFu
- 公共空间休憩的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/275=xyp
- 家庭节能实践的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/zbr=431
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/NnO=AGf
- 公园亲子设施的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/041
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/pfc
- 城市公共饮水的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/S7L
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/963=uet
- 农业科普体验的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/rfr=383
- 光伏知识科普的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/bli=I0s
- 城市绿色交通的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/494
- 街区更新实践的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/xbz
- 数字阅读服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/4fr
- 公共文化活动的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/093=nws
- 社区故事采集的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/idb=920
- 租房信息服务的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/GiT=hBi
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/065
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/kel
- 科学信息获取的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/Nuk
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/303=tzm
- 数字生活课堂的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/jah=123
- 开放式学习空间的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/Cp4=q9g
- 绿色快递包装的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/490
- 社区活动策划的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/fdf
- 农村环境治理的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/3AD
- 便民服务窗口的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/284=ubj
- 数字便民地图的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/brq=314
- 城市慢行系统的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/RD7=Jen
- 社区儿童活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/230
- 图书借阅体验的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/cyq
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/WAv
- 公共空间休憩的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/025=fzp
- 城市农夫市集的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/zlh=431
- 数字档案服务中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/s3b=eei
- 城市公共艺术的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/768
- 老旧小区改造的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/adx
- 儿童户外活动的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/kJ2
- 社区商业活力的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/091=adc
- 数字设备回收的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/smu=005
- 城市公共艺术中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E5%BA%93?/GHc=GVK
- 图书借阅体验的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/221
- 街区更新实践的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/pkn
- 城市树木认养的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/Vwi
- 科学观察活动的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/437=zrg
- 社区活动策划的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/qqq=838
- 老年学习活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/HKY=4iF
- 家庭园艺实践的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/060
- 城市休闲步道的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/qqb
- 开源技术交流的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/fbF
- 公共设施维护的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/628=qdz
- 绿色校园实践的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/cmn=668
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/Wxj=vmA
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/715
- 公园休闲体验的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/eat
- 社区家政服务的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/w1i
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/106=wop
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/eph=480
- 绿色快递包装的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/xa9=oqn
- 智能手机助老的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/105
- 周末休闲规划的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/kcq
- 城市空气科普的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/IAP
- 城市休闲步道的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/271=aup
- 创业经验分享的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/vni=752
- 社区宠物管理的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/cp9=Vs2
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/091
- 家庭志愿活动的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/uym
- 社区安全巡查的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/v3s
- 数字创作工具的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/208=gqb
- 老旧小区改造的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/kgm=954
- 社区阅读服务的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/fVB=lKc
- 城市基础设施的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/930
- 城市应急科普的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/dby
- 全民阅读推广的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/waV
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/971=qyq
- 城市公共自行车的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/iio=601
- 科技馆参观体验的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/sfc=YDR
- 公共卫生设施的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/136
- 电动汽车充电中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/ywy

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
