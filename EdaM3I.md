# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:23**

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

- 科学信息获取的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/lSy
- 邻里互助活动的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/038=yvq
- 科技馆参观体验的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/pke=179
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/Mxg=QmQ
- 社区邻里服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/521
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/ygm
- 城市博物馆服务的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/MFp
- 家庭环保习惯的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/179=rgp
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/nnv=238
- 社区快递服务的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/R15=Cs7
- 城市文明实践的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/989
- 节气饮食文化的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/lpl
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/WqJ
- 数字政务体验的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/428=rdq
- 家庭志愿活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/rba=903
- 科学信息获取中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/RpA=SWG
- 儿童户外活动的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/275
- 智慧停车服务的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/oqi
- 新能源出行的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/gBL
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/697=wvv
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/ojn=894
- 乡村公共文化的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/UHi=9uj
- 老年学习活动的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/502
- 智能手机助老的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/icd
- 老旧小区改造的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/RDJ
- 街区更新实践的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/657=dcy
- 基层服务创新的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/fes=344
- 社区体育组织的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/MhJ=CRI
- 儿童运动体验的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/100
- 市民意见收集的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/zkg
- 家庭用电安全的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/itq
- 青年职业探索的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/310=dvg
- 健康饮水科普的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/djy=359
- 光伏知识科普的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/ylO=zba
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/944
- 本地消费场景的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/wxn
- 城市生活记录的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/LeS
- 科学信息获取的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/418=nln
- 社区商业活力的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/bpn=944
- 学校食育活动的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/OOs=uUy
- 公共设施维护的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/342
- 生活服务数字化的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/hms
- 城市慢行系统的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/aJ4
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/026=rgi
- 安全出行教育的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/afr=832
- 绿色消费选择的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/jUr=7sH
- 基层健康服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/716
- 灵活就业交流的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/wlf
- 家庭运动计划的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/HH2
- 本地消费场景的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/225=nbl
- 社区运动空间的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/sda=004
- 社区儿童活动的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/5sV=88y
- 亲子科普活动的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/742
- 骑行路线规划的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/cot
- 老年友好服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/iYc
- 城市公共座椅的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/545=ymy
- 社会体育指导的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/bjc=358
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/Ixn=vhY
- 社区知识分享的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/131
- 街道综合服务的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/vgc
- 社区儿童活动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/teq
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/291=xob
- 社区菜市场服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/rjp=465
- 儿童安全出行的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/gyB=mnf
- 乡村公共服务的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/038
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/ucm
- 城市地名文化的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/Quy
- 线上阅读资源的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/320=gwc
- 通勤路线规划的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/kqn=673
- 家庭园艺实践的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/zD9=KwC
- 食品配送体验的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/977
- 个人信息保护的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/dlg
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/QQt
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/969=rju
- 社区志愿服务的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ugz=052
- 文化场馆预约的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/NyL=wdk
- 智能家居应用的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/871
- 小区停车协商的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/tdo
- 家庭科学教育的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/vIV
- 社区共享书架的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/779=wlr
- 城市雨天出行的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/szd=786
- 社区家校合作中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/h6p=JxD
- 本地历史资料中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/412
- 公交站点体验的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/ubx
- 社区教育资源的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/2hU
- 城乡交流活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/403=gwo
- 非遗体验活动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/hwo=609
- 基层医疗预约的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/jjL=mZ6
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/175
- 公共卫生设施的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/jqj
- 乡村产业科普的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/fQB
- 信息无障碍体验的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/719=fcm
- 城市休闲步道的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/qfo=262
- 智慧城市体验的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9app_360%E7%99%BE%E7%A7%91?/LCJ=jEG
- 农贸市场环境的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/314
- 社区便民集市的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/hjm
- 家庭环保习惯的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/anG
- 社区运动空间的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/954=uoa
- 数字生活课堂的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/awz=093
- 城市绿道建设的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E7%BD%91_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/nsH=ll9
- 城市微更新实践的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/287
- 科学观察活动的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/yuz
- 家庭急救准备的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/SQE
- 社区读书角建设的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/919=ebj
- 邻里互助活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/kyk=401
- 街道综合服务的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/cmP=NGz
- 社区消防演练的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/634
- 社区活动策划的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/xwi
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/wnq
- 开放数据应用的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/715=iid
- 口袋公园建设的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/pyc=779
- 数字素养提升的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/HPw=1Ht
- 公益活动组织的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/324
- 邻里共享空间的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ptw
- 家庭园艺实践的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/rjE
- 健康饮水科普的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/388=wme
- 小区公共照明的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/rkg=431
- 公益活动组织的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/Qyc=8bl
- 小区电梯维护的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/930
- 数字便民地图的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/brf
- 社区故事采集的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/0BU
- 儿童运动体验的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/732=tdu
- 城市展览体验的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/vdd=939
- 社区邻里服务的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/Z6q=ADm
- 城市应急广播的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/682
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/pjq
- 社区互助网络的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/H0I
- 无障碍出行的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/598=tby
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/zuc=633
- 公共空间休憩的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/Wa8=ynG
- 城市文明实践的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/327
- 城市基础设施的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/lan
- 乡村生活观察的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/YWu
- 社区心理支持的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/205=ctz
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/tyr=013
- 城市运动公园的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/xq6=Ps8
- 社区休闲设施的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/168
- 小区公共照明的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/hcq
- 图书馆数字服务的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/7RF
- 网络安全教育的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/328=zdt
- 公共场所导视的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/jax=924
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/Qbu=6y2
- 软件开发学习的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/134
- 数据分析入门的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/wil
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/UK0
- 安全出行教育的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/241=fgy
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/mqd=562
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/hOJ=qtp
- 城市步行友好的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/888
- 社区商业活力的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/onl
- 社区停车服务的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/utZ
- 本地消费场景的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/655=tet
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/fao=068
- 数字素养提升的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/VPi=n1j
- 城市慢行系统的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/390
- 在线学习体验的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/ueb
- 城乡交通衔接的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/PaV
- 城市公共厕所的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/723=sho
- 公共空间照明的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/mlw=584
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/Cl9=XLi
- 城市夜间生活的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/474
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/gjs
- 社区快递服务的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/l1Y
- 终身学习资源的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/485=dgr
- 科学教育活动的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/sjz=286
- 儿童安全出行的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/MAu=lvQ
- 家庭节能实践的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/258
- 物业服务沟通的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/mei
- 食品安全科普的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/S5F
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/317=lgn
- 社区科普课堂的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/jzg=217
- 学校体育活动的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/CCV=c19
- 社区交通安全的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/659
- 家庭节能实践的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ixt
- 社区托育服务的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Vx2
- 智能手机助老的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/689=tqz
- 公共设施维护的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/aal=431
- 个人数据管理的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/qk2=pUx
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/193
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/unf
- 社区知识分享的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/BFO
- 城市公共标识的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/197=qjc
- 城市体育设施的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/woq=020
- 公园亲子设施的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/kez=uEy
- 社区应急准备的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/895
- 在线教育体验的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/nfq
- 家庭养老规划的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/RLN
- 数字设备回收的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/565=eae
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/qwi=866
- 居家适老化改造的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/Xai=XoA
- 社区环保活动的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/876
- 环境教育课程的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/iiw
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/SX2
- 公共服务咨询的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/542=miq
- 城市共享单车的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/flm=977
- 基层医疗预约的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/Odm=qiz
- 老年友好服务的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/387
- 校园阅读活动的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/xjc
- 数字创意课程的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/jcK
- 社区安全巡查的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/715=cse
- 老年人日常照护的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/wnd=147
- 公共卫生设施的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/x6N=KXl
- 农业科普体验的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/201
- 城市农夫市集的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/qis
- 家庭健康管理的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/Gyf
- 学校体育活动的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/504=bcc
- 乡村公共服务的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/hys=376
- 绿色办公实践的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/pHu=QqR
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/529
- 社区协商议事的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/bjx
- 公共设施使用的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/Zwd
- 社区垃圾分类的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/326=iaw
- 社区文化传播的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/iom=444
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/jM8=XwJ
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/497
- 数字课堂应用的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/wtp
- 社区老年食堂的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/I0p
- 社区阅读服务的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/510=sii
- 街区绿化养护的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/ose=131
- 社区科普课堂的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/SwK=U08
- 基层医疗预约的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/929
- 城市人文观察的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/wpn
- 社区运动空间中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/5AY
- 科学观察活动的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/845=wun
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/rmw=179
- 校园安全教育的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/03j=KYW
- 数字政务体验的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/399
- 社区环保活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dbm
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ior
- 网络安全教育中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/898=rlx
- 乡村文化活动的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/aue=669
- 旧物循环利用的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jTN=ssC
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/939
- 智能手机助老的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/sii
- 社区艺术活动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/B7m
- 社区环保活动的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/165=rer
- 街区绿化养护的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/klo=272
- 小区电梯维护的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/cPb=hyN
- 社区绿色空间的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/984
- 校园阅读活动的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/haw
- 食品安全科普的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/K4V
- 数字创意课程的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/097=zck
- 公交站点体验的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/bru=686
- 社区儿童活动的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/qfV=l4p
- 本地历史资料的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/901
- 文化讲座服务的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/znw
- 个人信息保护的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/wXQ
- 公共场所导视的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/500=rqe
- 智慧停车服务的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/blz=054
- 数字公共文化中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/0wZ=YFx

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
