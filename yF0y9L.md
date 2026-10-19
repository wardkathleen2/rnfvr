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

- 科学运动指导从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/550
- 城市绿道建设的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/aki
- 科学健身方法的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/2xg
- 城市夜间照明的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/149=kig
- 社区艺术活动的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/rvp=436
- 城乡公共服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AE%98%E6%96%B9%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/O7x=vdQ
- 城市公共厕所的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/127
- 城市生活记录的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/ede
- 文化讲座服务的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/hRl
- 城市公共标识的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/376=bwx
- 社区便民集市的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/dlt=143
- 社区安全巡查的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E7%9B%B4%E8%90%A5%E8%80%81%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/WyE=aGu
- 乡村文化活动的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/084
- 家庭安全提示的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/zrk
- 图书借阅体验的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/UJl
- 全民健身活动的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/988=mmc
- 家庭防灾准备的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/urg=575
- 电动汽车充电的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/y8K=lqI
- 绿色校园实践的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/177
- 食品安全科普的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/sos
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/VHX
- 城市公共艺术的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/495=igi
- 邻里共享空间的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/jki=655
- 社区设施共享的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_520%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/ABb=sB7
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/656
- 家庭健康管理的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/pac
- 儿童友好空间的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/kga
- 公共服务沟通的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/356=nyn
- 科学健身方法的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/jee=253
- 劳动教育实践的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%EF%BC%88KK%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/SZR=uib
- 日常摄影记录的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/330
- 家庭食品保存的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/hks
- 社区艺术活动的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/8uJ
- 乡村电商实践的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/276=avd
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/jvw=242
- 街头绿植养护的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/Rpn=0dv
- 农业科普体验的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/768
- 节日文化体验的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/ojs
- 青年职业探索的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/hr9
- 城市住房服务的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/851=utk
- 城市公共饮水的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/zql=880
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9App%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/o4S=3kb
- 乡村文化活动的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/636
- 社区托育服务的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/pwn
- 数字生活课堂的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/2l5
- 城市公共空间的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/775=uwl
- 家庭理财科普的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/ykt=568
- 老旧小区改造的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/xW4=7Lh
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/639
- 健康信息获取的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/umx
- 社区菜市场服务的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/KBk
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/493=ezw
- 城市文化路线的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/meh=241
- 社区商业活力的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/iEQ=zSu
- 读书会组织的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/904
- 基层医疗预约的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/xur
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/xja
- 社区托育服务的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/083=vsw
- 终身学习资源的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/vvp=796
- 生成式工具使用的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/ZDz=9My
- 青少年科技社团的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/201
- 儿童安全出行的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/nvp
- 街区更新实践的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/GXt
- 公共卫生设施的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/187=ztk
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/lsu=027
- 老年人出行服务的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/FxV=ChA
- 社区故事采集的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/299
- 儿童友好空间的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/got
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/sxB
- 社区便利生活的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/640=rlf
- 数字生活课堂的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/emc=625
- 城市慢跑路线的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/Cvr=AUG
- 城市体育设施的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/163
- 社区商业活力的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ari
- 跨代沟通活动的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/2V9
- 物业服务沟通的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/865=apj
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/twz=433
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/cCr=y3G
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/267
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/lyp
- 城市文明实践的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/7P6
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/861=txh
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/kzh=015
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/jaO=EJg
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/044
- 旧物循环利用的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/ujl
- 青少年心理健康的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/lMD
- 社区文化节活动的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/500=wmk
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/woj=676
- 社区防暑服务的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/fcI=tF2
- 社区运动空间的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/401
- 便民维修服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/ggx
- 城市生活服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/s8U
- 家庭科学教育的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/697=vbp
- 地方旅游导览的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/dkc=031
- 社区便民集市的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/IjO=b6p
- 食品安全科普的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/483
- 儿童友好街区的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/hvr
- 基层医疗预约的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/2UK
- 社区文化传播的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/553=wrk
- 数字课堂应用的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/wsr=635
- 家庭园艺实践的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/E3D=opf
- 城市夜间照明的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/467
- 生活技能分享的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/czq
- 无障碍信息设计的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/xUT
- 城市共享单车的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/040=uyc
- 非遗体验活动的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/qgn=622
- 城市便民驿站的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/Z1m=wvW
- 本地历史资料的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/652
- 公共服务数字化的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/sny
- 乡村公共服务的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/VZ0
- 城市公共饮水的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/686=dok
- 网络信息辨识的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/ezl=759
- 社区法律科普的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/Xah=0BA
- 乡村教育资源的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/233
- 社区防暑服务的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/hnf
- 社会体育指导的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/c6q
- 社区应急准备的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/374=jxv
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/hma=017
- 公共交通接驳的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/Trb=bVO
- 乡村公共文化的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/103
- 老旧小区改造的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/agv
- 公共卫生设施的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/DO6
- 气象科普传播的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/777=krk
- 基层健康服务的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/ryq=477
- 社区活动策划的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/VhA=uQj
- 城乡公共服务的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/881
- 劳动教育实践的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/ktk
- 公园无障碍服务的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/Vsd
- 科学运动指导的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/030=rod
- 光伏知识科普的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/lxa=798
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/Kb7=JLD
- 药品使用科普的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/454
- 社区科普课堂的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/lxf
- 城乡公共服务的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/CNU
- 社区共享书架的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/908=imn
- 绿色校园实践的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/bxh=306
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/7mN=MKu
- 科普展览体验的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/014
- 城市休闲步道的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/udw
- 环境教育课程的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/1f1
- 城市建设科普的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/011=liu
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/crr=633
- 社区共享书架的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/pDe=t4J
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/138
- 个人时间管理的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/rpd
- 城市建设科普的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/Fgm
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/612=hqj
- 青少年科普实践的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/tcp=462
- 城市公共空间的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/EuS=Ijx
- 智能手机助老的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/335
- 文明养宠科普的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/uau
- 文化场馆预约的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/BFO
- 城市步行友好的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/520=kum
- 环境教育课程的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/ynw=156
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/hN0=81S
- 数字支付体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/044
- 小区电梯维护的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/xds
- 公园亲子设施的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/oSG
- 网络信息辨识的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/305=vgx
- 开放式学习空间的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/fnh=238
- 城市公共饮水的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/Ys7=Hfj
- 城市公共空间的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/610
- 城市运动公园的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/szx
- 日常摄影记录的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/sWb
- 社区花园共建的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/033=trf
- 公共空间安全的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/kgd=177
- 社区运动空间的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BD%91%28kuai3%29_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/S6d=zHw
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/345
- 居家适老化改造的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/jda
- 本地消费场景的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/KDd
- 老年智能设备的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/407=qma
- 地方旅游导览的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/sbm=884
- 非遗体验活动的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/6DY=anT
- 职业技能学习的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/462
- 公共交通接驳的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/sip
- 生活技能分享的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/3K9
- 社区阅读服务的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/190=ncr
- 儿童运动体验的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/jmn=997
- 本地消费场景的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/byz=SsY
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/829
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/xpr
- 软件开发学习的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/iDl
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/664=jfs
- 社区老年食堂的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/lei=133
- 家庭环保行动的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/ykN=v1C
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/320
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/gzy
- 周末休闲规划的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/JBg
- 城市体育设施的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/995=wel
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/sqg=360
- 农村环境治理的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/hbM=tIh
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/074
- 公共服务数字化的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/xpm
- 城市文化路线的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/0xt
- 公共空间安全的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/781=wjb
- 青年志愿活动的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/mdb=086
- 青少年编程学习的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/ekA=ayL
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/065
- 公共空间安全的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/yho
- 社区绿色空间的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/Yel
- 街头绿植养护的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/870=jii
- 社区教育资源的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/hea=182
- 公共图书馆服务的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/H32=0hr
- 乡村公共阅读的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/941
- 老年友好服务的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/zco
- 开放数据应用的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/30R
- 电动汽车充电的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/781=vzr
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/gms=029
- 开放数据应用的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/8V2=4oe
- 社区学习活动的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/524
- 家庭安全提示的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/uqc
- 社区设施共享的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/hYJ
- 城市文化路线的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/563=tqx
- 公园休闲体验的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/kuk=440
- 社区商业活力的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/qE0=NpA
- 小区停车协商的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/310
- 学校食育活动的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/nyv
- 科学健身方法的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/GBo
- 社区宠物管理的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/000=vkx
- 小区电梯维护的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/ncp=938
- 公共服务沟通的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/BH1=5gu
- 家庭食品保存的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/888
- 街道综合服务的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/fob
- 环境教育课程的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/YIm
- 城市骑行环境的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/860=etj
- 社区商业活力的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/rfq=177
- 家庭环保习惯的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/TnY=jYS
- 青年志愿活动的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/976
- 全民阅读推广的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ysn
- 开源技术交流的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/6y3
- 应急物资管理的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/948=lbr
- 社区商业活力的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/pyb=004
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/hZI=PHJ
- 生活技能分享的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/394
- 基层服务创新的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/rxp
- 城市公共饮水的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/rgR
- 个人数据管理的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/368=req
- 数字生活课堂中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/ohe=469
- 智慧停车服务的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/hW4=zvW
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/279
- 儿童运动体验的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/sps
- 基层健康档案的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/rNZ
- 节假日出行安排的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/400=qka
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/wyd=137
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/TEQ=Wns
- 社区读书角建设的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/606
- 城市地名文化的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/hln
- 电动汽车充电的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/OIE
- 社区便民服务的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/017=qsf

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
