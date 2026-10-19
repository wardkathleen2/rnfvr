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

- 公共服务指南从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/704
- 家庭急救准备的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/rph
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/dCe
- 户外活动组织中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/122=uef
- 城市绿色交通的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/gcw=902
- 城市生活记录的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/HGK=lHQ
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/574
- 灵活就业交流的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/bri
- 社区安全巡查的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/vXI
- 邻里共享空间的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/740=kpf
- 居家适老化改造的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/tmv=045
- 职业技能学习的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/o4r=Eay
- 儿童运动体验的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/290
- 生活技能分享的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/jxe
- 个人时间管理的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/QDh
- 老年学习活动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/912=cpq
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/jqa=731
- 社区垃圾分类的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/tn9=Akx
- 便民维修服务的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/648
- 乡村产业科普的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/mjj
- 校园社团活动的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/uqf
- 基层健康服务的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/650=vds
- 居家适老化改造的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/grn=324
- 城市可持续生活的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/5tu=6A8
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/441
- 社区花园共建的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/bmc
- 绿色办公实践的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/iBy
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/476=sed
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/yha=001
- 城市展览体验的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/evD=QWf
- 个人信息保护的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/377
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/yyz
- 城市农夫市集的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/RdR
- 公园无障碍服务的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/986=dja
- 本地历史资料中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/mqd=769
- 公共设施维护的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/V3M=4Xx
- 节能生活方式的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/430
- 社区便民服务的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/pax
- 农贸市场环境的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/LoJ
- 家庭节能设备的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/976=ijy
- 地方旅游导览的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/zsm=969
- 社区宠物管理的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/J39=wi5
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/564
- 社区便民服务的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/xxd
- 社区运动空间中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/kPO
- 社区设施共享的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/142=nip
- 城市微更新实践的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/syv=052
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/UCH=7sP
- 家庭运动计划的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/164
- 便民维修服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/hjr
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/1gf
- 家庭科学教育的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/524=yxm
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/zyb=087
- 社区应急准备的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/dsc=Jul
- 社区法律科普的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/757
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/ygz
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/utl
- 家庭志愿活动的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/610=ddk
- 老年人日常照护的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/xev=222
- 智能手机助老的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/vsh=g5I
- 城市应急广播的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/640
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/udr
- 电子商务服务的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/w7A
- 线上办事服务的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/018=vev
- 个人数据管理的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/aja=651
- 消防知识宣传中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/JFz=ulE
- 非遗体验活动的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/776
- 城市雨天出行的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/zmb
- 健康步道使用的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/ObB
- 传统节日科普的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/477=xbb
- 家庭环保习惯的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/ogn=781
- 社区故事采集的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/Lmh=UHK
- 数字资源检索的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/713
- 城市空气科普的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/kto
- 老年人文化生活的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/bxz
- 公共设施维护的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/951=ygd
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/bea=781
- 便民服务窗口的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/l7o=OSx
- 城市公共艺术的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/694
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/mxv
- 地方民俗记录的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/trs
- 数据分析入门中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/147=hwy
- 城市文化路线的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/oap=835
- 人工智能科普的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/xkD=OP0
- 健康饮水科普的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/961
- 城市文明实践的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/glv
- 社区消防演练的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/0hG
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/053=mjv
- 在线学习体验的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/hrn=758
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/RFx=O4a
- 社区心理支持的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/797
- 非遗体验活动的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/mms
- 社区文化传播的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/W1C
- 街区绿化养护的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/672=mon
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/iwi=526
- 机器人科普活动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/CVz=x2w
- 科学信息获取的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/785
- 生活垃圾减量的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/efn
- 数字支付体验的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/Bdk
- 数字素养提升的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/955=usi
- 便民服务窗口的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/xcn=435
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/pFK=HoD
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/425
- 公园亲子设施的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/iys
- 家庭网络使用的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/YhG
- 城市共享单车的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/573=rnx
- 城市文明出行的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/iru=933
- 地方旅游导览的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/ud2=854
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/283
- 绿色快递包装的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/qph
- 读书会组织的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/fxT
- 公共交通接驳的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/306=orj
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ixj=234
- 乡村产业科普的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/3p9=EP6
- 节约用水实践的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/736
- 街区更新实践的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/ghg
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/Sps
- 小微企业服务的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/590=amr
- 节约用水实践的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/ibk=454
- 社区老年食堂的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/Ny5=GM6
- 社区花园共建的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/714
- 城市公共自行车的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/rez
- 城市展览体验的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/ee4
- 校园安全教育的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/334=qfu
- 小区停车协商的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/ffz=937
- 无障碍出行的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/z6j=6uc
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/285
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/kfy
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/U4y
- 公园无障碍服务的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/312=ann
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/mds=170
- 青少年科技社团的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/cSi=dQP
- 邻里互助活动的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/116
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/owz
- 街区道路维护的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/Axw
- 城市应急广播的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/482=rdc
- 公共健身器材的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/kdg=276
- 家庭健康科普的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/pj8=x3t
- 社区文化传播的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/561
- 老年学习活动的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/orn
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/AWH
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/119=ums
- 在线教育体验的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gnb=677
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rPD=mpU
- 公共空间导览的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/975
- 城市噪声观察的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/hhj
- 乡村公共文化的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/w4W
- 社区消防演练的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/548=lln
- 城市便民驿站的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/jlw=411
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/FUv=W1f
- 城市夜间生活的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/521
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/zml
- 城市适老服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/A0O
- 社区交通安全的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/884=pcc
- 新能源知识普及的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/iba=291
- 城市公共空间的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/GlF=PUJ
- 全民阅读推广的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/086
- 城市展览体验的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/sep
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/b1a
- 乡村文化活动的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/962=jpe
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/snh=291
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/k9B=q3Y
- 公共交通接驳的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/016
- 城市步行友好的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/urs
- 乡村教育资源的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/Byt
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/208=kni
- 便民信息查询的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/gzv=373
- 城市公共艺术的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/ssZ=5zU
- 社区安全巡查的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/313
- 健康步道使用的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/aat
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/yVb
- 儿童安全出行的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/103=dlr
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/grs=619
- 地方美食文化的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/CDz=YGT
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/734
- 乡村文化活动的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/hzz
- 健康信息获取的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/nbs
- 公共设施维护的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/428=kih
- 公共交通接驳的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/zns=704
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/X5r=P3R
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/882
- 图书馆活动策划的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/ywz
- 数字课堂应用的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/ruN
- 基层健康服务的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/251=dda
- 老年人出行服务的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/zqc=803
- 街区小店体验的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/H6t=F7F
- 科学健身方法的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/180
- 数字便民地图的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/qxy
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/xVj
- 社区环保活动的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/217=zkj
- 图书馆数字服务的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/ttg=364
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/dwo=izn
- 城市公共厕所的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/106
- 社区活动空间的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/sgr
- 社区互助网络的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/qv8
- 学校食育活动的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/324=klw
- 数字支付体验的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/ixh=804
- 公共空间照明的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/x1B=TnU
- 社区安全巡查的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/498
- 课后服务体验的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/gwe
- 社区体育组织的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/yq2
- 社区知识分享的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/990=eeh
- 街区更新实践的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/joj=457
- 社区绿色空间的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/Hze=or1
- 社会体育指导的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/639
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/ewm
- 青少年户外教育中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/910
- 社区庭院绿化的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/011=zqp
- 运动安全知识的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/rda=078
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/QtA=zdu
- 在线教育体验的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/631
- 社区学习活动的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/nqq
- 城市休闲步道的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/Pdv
- 城乡公共服务的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/506=das
- 职业技能学习的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/sso=833
- 社区修缮行动的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/Mia=vkL
- 青年志愿活动中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/852
- 社区花园共建的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/yzv
- 公交无障碍服务的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/THb
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/678=haj
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/gsn=940
- 社区阅读服务中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/36t=Zkk
- 城市公共饮水的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/033
- 市民热线服务的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/ghg
- 本地消费场景的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/nY5
- 公共服务数字化的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/408=pof
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/uvs=882
- 家庭志愿活动的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/Bhx=yF9
- 线上阅读资源的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/266
- 公共空间导览的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/dul
- 数字创作工具的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/ENI
- 智慧城市体验中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/233=jru
- 家庭健康管理的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/cpq=771
- 数据分析入门的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/84R=TI6
- 社区儿童活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/335
- 数字艺术创作的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/nee
- 图书馆活动策划的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/cm3
- 社区邻里服务的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/069=cix
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/nnl=119
- 街区更新实践的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/NCe=ssD
- 社区法律科普的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/776
- 城市博物馆服务的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/hwk
- 城市共享单车的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/ZBG
- 社区便民集市的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/564=ros
- 社区协商议事的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/pqt=249
- 全民健身活动的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/e82=lxS
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/003
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/uap
- 智慧城市体验的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/eBf
- 信息无障碍体验的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/651=wqq

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
