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

- 基层服务创新的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/742
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/uin
- 社区花园共建的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/7jv
- 城市慢行系统的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/962=tzm
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/auk=360
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/VEd=UNE
- 城市地名文化的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/292
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/uqy
- 城市共享单车的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/PHA
- 城市公共座椅中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/184=let
- 绿色消费选择的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/scg=401
- 在线学习体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/UcJ=X2g
- 城市水环境观察的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/670
- 远程协作工具的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/xzj
- 科学信息获取的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/1Xm
- 社区学习活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/733=uos
- 城市树木认养的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/oqz=294
- 图书馆活动策划的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/0Fc=Gem
- 农产品品牌传播的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/047
- 城市体育设施的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/luo
- 基层健康服务的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/bcI
- 城市体育设施的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/864=kbo
- 社区便利生活的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/smy=362
- 家庭养老规划的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%B8%AE%E6%88%91%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93?/YD9=TJ5
- 城市人文观察的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/057
- 个人时间管理的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/dic
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/WiK
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/599=ruq
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/tfa=217
- 市民热线服务的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/x3x=Irx
- 儿童安全出行的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/622
- 儿童安全出行中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/gzu
- 数字生活课堂的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/nN6
- 街头绿植养护的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/621=nve
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/rat=564
- 社区垃圾回收的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%A8%A1%E6%8B%9F%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/C8M=8iV
- 社区互助网络的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/929
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/dnj
- 社区花园共建中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Rqn
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/597=fea
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/gnp=280
- 儿童安全出行的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%88%91%E8%A6%81%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/qHi=emP
- 乡村生态观察的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/460
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/kwd
- 社区消防演练的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/4Us
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/798=mad
- 气象科普传播的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/awl=987
- 生活技能分享的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/WKn=gPb
- 老年数字阅读的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/329
- 社区邻里服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/vnz
- 健康信息获取的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/vD0
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/863=bam
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/xuk=529
- 街区小店体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/BY7=Cpx
- 社区活动策划的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/587
- 数字学习资源的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/tmp
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/Ygm
- 城市夜间照明的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/960=blg
- 社区教育资源的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/dwm=142
- 家庭运动计划的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/F1T=EkB
- 生成式工具使用的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/906
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/ddh
- 公交站点体验的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/Jav
- 亲子阅读活动的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/538=hdy
- 数字地图应用的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/ozn=892
- 城市绿色交通的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/lCO=gg6
- 环境教育课程的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/055
- 公共空间照明的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/cax
- 健康步道使用的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/QUt
- 线上阅读资源的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/386=jpl
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/uja=979
- 公共服务预约的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/U5V=tts
- 城市文明出行的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/959
- 城市文化路线的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/jnq
- 休闲运动入门的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/JJ9
- 居民健康教育的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/615=frl
- 城市夜间照明的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/omd=244
- 数字素养提升的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/GbA=k99
- 乡村产业科普的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/464
- 便民维修服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/qnr
- 食品配送体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/IDh
- 居家适老化改造中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/944=ott
- 电子商务服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/ipv=499
- 城市共享单车的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/umZ=ZLQ
- 节约用水实践的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/090
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/wdx
- 休闲运动入门的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/vrW
- 家庭环保行动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/977=lkl
- 社会体育指导的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/cqd=531
- 小区停车协商的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BD%93%E5%BD%A9%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/W14=Bxm
- 社区商业活力的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/275
- 线上阅读资源的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/imp
- 非遗体验活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/VlG
- 社区修缮行动的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/052=sls
- 儿童友好空间的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/ili=210
- 社区公共议事的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/gPb=XLm
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/291
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/ylt
- 家庭运动计划的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/OtP
- 乡村产业科普的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/475=uky
- 城市空气科普的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/ehh=048
- 社区志愿服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9959%E7%90%AA_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/lX2=8hp
- 口袋公园建设的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/730
- 社区生活指南的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/pkk
- 小区电梯维护的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/6SD
- 职业技能学习中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/580=pmu
- 电动汽车充电的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/exz=322
- 无障碍出行的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/3gQ=2hf
- 便民维修服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/280
- 地方旅游导览的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/wzf
- 健康饮食教育的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/Bqg
- 日常摄影记录的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/724=qjg
- 社区文化节活动的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/qen=766
- 城市展览体验的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/rL8=qtH
- 社区活动空间的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/956
- 社区读书角建设的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/url
- 在线学习体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/42F
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/815=vbf
- 环境教育课程的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/gyo=946
- 健康饮水科普的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/r2G=GGQ
- 文明养宠科普的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/652
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cur
- 社区养老服务的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Xmb
- 软件开发学习的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/555=vjq
- 科技馆参观体验的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zqp=080
- 乡村文化活动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E8%BD%AF%E4%BB%B6_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vvS=prj
- 数字档案服务的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/533
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/yzl
- 青少年户外教育的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/WNR
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/080=cna
- 公园亲子设施的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/btr=275
- 科学教育活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/E1B=aEP
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/639
- 城市夜间照明中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/eib
- 城市步行友好的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/btH
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/881=peu
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/zmj=492
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/0af=dFe
- 数字公共文化的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/939
- 科普展览体验的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/kze
- 城市树木认养的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/ygv
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/121=rnc
- 社区慢性病防控的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/cyk=674
- 家庭健康科普的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/muE=DtO
- 骑行路线规划的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/595
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/uqy
- 就业技能培训的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/GTg
- 软件开发学习的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/628=wch
- 气象科普传播的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/hug=278
- 社区文化传播的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/zt2=AfR
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/602
- 学校体育活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/efl
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/An6
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/389=kxv
- 城市慢行系统的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/exf=766
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E5%86%9C%E4%B8%9A?/w12=tj4
- 本地消费场景的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/073
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/rfy
- 社区心理支持的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/02E
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/938=izf
- 社区文化节活动的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/ufx=235
- 智慧停车服务的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/PcQ=4JJ
- 公共服务咨询的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/500
- 城市树木认养的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/vrg
- 农业科普体验的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/GHX
- 公交站点体验中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/853=zon
- 社区阅读服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/fib=455
- 乡村生活观察的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/DT7=LEo
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/654
- 课后服务体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/gbh
- 街区更新实践的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/zZ8
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/227=wwm
- 个人信息保护的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/twt=653
- 邻里共享空间的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/QyJ=t6g
- 城市文明实践的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/506
- 城市体育设施的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/qyc
- 公共空间休憩的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/04u
- 公共文化活动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/944=ewq
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/iwr=400
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%9C%9B?/vEy=9xR
- 数字公共文化的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/782
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/oik
- 绿色办公实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/hrb
- 小微企业服务的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/722=lci
- 城市适老服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/hyv=190
- 社区故事采集的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/aTr=X1W
- 家庭健康管理的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/807
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/xqw
- 科学信息获取的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/Pzj
- 社区停车服务的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/390=vjx
- 健康信息获取的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/mdx=823
- 公共场馆服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_360%E8%A7%86%E9%A2%91?/lc5=Fi3
- 生成式工具使用的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/507
- 青年职业探索中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/zjy
- 社区休闲设施的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/lHR
- 城市文明出行的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/884=ewj
- 科学观察活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/teg=033
- 社区交通安全的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/UxT=bJl
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/907
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/ynx
- 城市夜间照明的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/NNE
- 口袋公园建设的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/211=nvi
- 家庭网络使用的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/kze=850
- 家庭健康管理的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/hhj=d4I
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/033
- 乡村公共服务的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/xva
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/QFp
- 智能家居应用的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/525=qxx
- 节日文化体验的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/tre=975
- 公共空间照明的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/gIz=PVi
- 公共交通信息服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/811
- 社区互助网络的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/tfb
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/1ud
- 家庭食品保存的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/727=mre
- 社区活动策划的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/djf=923
- 城市步行友好的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/UyC=ss7
- 健康信息获取的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/765
- 数据分析入门的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/qkf
- 乡村公共阅读的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/Tod
- 本地消费场景的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/361=wjy
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/lbv=373
- 医院导诊服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/rYv=lMV
- 生活垃圾减量的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/428
- 城市绿道建设的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/dly
- 科普展览体验的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/4wT
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/560=cbn
- 社区知识分享的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/vns=725
- 急救知识普及的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Jgr=ZgD
- 在线教育体验的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/942
- 社区学习活动的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/six
- 电动汽车充电的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/iwB
- 绿色快递包装的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/314=zgn
- 社区停车服务的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/bxl=870
- 智慧城市体验的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/zOW=m4E
- 公园休闲体验的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/758
- 电动汽车充电的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xcq
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/WIh
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/899=ryl
- 公共服务数字化的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zwj=295
- 公共空间休憩的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/B8D=Opi
- 公共交通接驳的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/619
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/vkq
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/E9a
- 家庭志愿活动的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/575=vkv
- 城市微更新实践的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/ezz=888
- 城市应急科普的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/LWV=87j
- 乡村教育资源的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/572
- 城市夜间生活的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/kre
- 城市生活服务的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/30C
- 在线学习体验的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/368=lcl

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
