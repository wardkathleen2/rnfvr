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

- 旧物循环利用的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_77cc%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/fsb=613
- 公共文化活动的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_77cc%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/C10=3tY
- 家庭教育交流的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/027
- 儿童阅读角的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/fbs
- 劳动教育实践的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/HOQ
- 老年人文化生活的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/698=avo
- 老旧小区改造的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/ztd=231
- 家庭用电安全的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%925%E5%88%86_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/UOE=YT5
- 城市建设科普的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/600
- 光伏知识科普的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/mqf
- 地方旅游导览的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/pp7
- 老年人日常照护的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/856=bna
- 家庭消费规划的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/ddm=881
- 街道综合服务中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E6%8E%A8%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/JhS=VJ4
- 街道综合服务的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/710
- 健康饮水科普的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/jsv
- 公共空间休憩的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/rHD
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/306=iby
- 社区商业活力的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/nuu=380
- 市民意见收集的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E4%BA%9A%E5%B7%9E%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91ios_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/J01=Wx7
- 数字支付体验的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/492
- 城市应急科普的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/afi
- 家庭健康科普的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/BI1
- 开放数据应用的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/240=feq
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/gri=086
- 非遗课堂体验的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E8%B5%A2%E4%BA%9A%E8%B5%A2app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/FWF=TN2
- 社区生活指南中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/620
- 光伏知识科普的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/hbp
- 社区设施共享的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/nUh
- 终身学习资源的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/743=gny
- 老年学习活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/gua=541
- 城市步行环境的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/d2V=LcH
- 乡村电商实践的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/630
- 家庭运动计划的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/ufp
- 城市生活服务的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/P3J
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/840=zzv
- 开放数据应用中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/jum=788
- 终身学习资源的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%85%E8%B5%A2%E7%A7%98%E8%AF%80_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/65G=VU7
- 公共空间照明的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/536
- 社区防暑服务的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/gfq
- 急救知识普及的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/dd8
- 便民服务地图的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/310=wld
- 城市噪声观察的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/xxk=457
- 青少年编程学习的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9welcome_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/qDg=5eh
- 城市住房服务的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/597
- 科学信息获取的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/end
- 数字资源检索的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/NOp
- 社会体育指导的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/466=hir
- 数字地图应用的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/qbp=134
- 校园阅读活动的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/Hko=qXR
- 校园安全教育的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/223
- 城市公共空间的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/tok
- 农产品消费体验的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/JfJ
- 社区教育资源的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/688=cvz
- 城乡公共服务的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/lmm=136
- 地方美食文化中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/p3X=8qx
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/326
- 绿色校园实践的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/fpi
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/bMR
- 数字政务体验的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/374=hob
- 软件开发学习的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/wdv=154
- 数字创作工具的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/9V6=0gY
- 电子商务服务的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/974
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/qeb
- 数字公共文化的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/jLP
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/204=vir
- 城市人文观察的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/eks=654
- 公共空间休憩的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%A7%91%E6%8A%80?/cSF=hMz
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/644
- 节能生活方式的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/bse
- 家庭园艺实践的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/GcQ
- 城市文化路线的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/059=xxs
- 公园亲子设施的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/rsa=098
- 社区宠物管理的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/qa3=1sQ
- 家庭园艺实践的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/554
- 家庭健康管理的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/yaj
- 图书馆活动策划的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/Ij0
- 志愿服务平台的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/945=rtb
- 绿色生活实践的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/xsz=150
- 城市休闲步道中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/5DU=0uZ
- 城市住房服务的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/651
- 乡村生态观察的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/vsz
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/QcR
- 乡村文化活动的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/277=wfm
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/mcq=922
- 跨代沟通活动的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/oGc=dgE
- 智能手机助老的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/861
- 乡村文化活动的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/vpn
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/KxC
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/711=hlb
- 绿色生活实践的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/gui=927
- 儿童友好空间的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/io7=voK
- 儿童阅读角的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/233
- 开放式学习空间的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/lju
- 乡村电商实践中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/vQo
- 社区老年食堂的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/818=wht
- 公共服务数字化的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/kcd=329
- 智能家居应用的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/mdl=PIl
- 城市公共空间的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/612
- 城市公共艺术的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/blm
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/zXX
- 科学运动指导的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/102=pro
- 个人信息保护的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/zkz=367
- 邻里共享空间的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/oDx=Jlb
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/206
- 公共设施使用的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/ixn
- 家庭理财科普的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/XWO
- 图书借阅体验的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/798=bzl
- 社区休闲设施的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/cgs=458
- 图书借阅体验的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/QCW=Lw8
- 公共空间安全的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/733
- 居家防滑改造的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/xcs
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/tsV
- 社区应急准备的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/373=riq
- 本地历史资料的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/wsq=652
- 科学信息获取的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/uLO=FFD
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/046
- 社区垃圾回收的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/abe
- 公共服务指南的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/KH0
- 绿色校园实践的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/428=xeq
- 健康信息获取的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/xwe=342
- 家庭饮食安排的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/isV=yp7
- 数字便民地图的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/955
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/dbl
- 公共服务评价的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/3jr
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/156=mix
- 城市绿色交通的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/ail=024
- 在线教育体验的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/5dA=IOV
- 数字创作工具的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/846
- 数字学习资源的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/kmc
- 老年友好服务的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/cyC
- 家庭科学教育的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/118=omy
- 无障碍信息设计的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/xvi=879
- 城市博物馆服务的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A6%9C%E5%8D%95?/ZSK=u9N
- 骑行路线规划的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/679
- 城市社区治理的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/tge
- 智能家居应用的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/mo8
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/516=rgu
- 家庭环保习惯的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/gdc=218
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/XR3=3oE
- 城市公共自行车的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/849
- 城市社区治理的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/qdy
- 公交站点体验的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/8wu
- 城市基础设施的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/913=qnz
- 儿童友好空间的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/wyv=523
- 校园安全教育的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%96%80%E5%BD%A9%E7%A5%A8%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8%E7%B6%B2%E7%AB%99_%E5%93%94%E5%93%A9%E4%BF%A1%E8%B4%B7?/c4j=0yr
- 家庭运动计划的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/503
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/tvr
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/IM3
- 社区应急准备的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/372=xfb
- 社区阅读服务的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/wyn=672
- 通勤路线规划的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%BD%A9%E7%BD%91_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/z1j=1bR
- 非遗课堂体验的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/185
- 乡村生活观察的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/bdm
- 儿童运动体验的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/RKf
- 家庭教育交流的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/098=bql
- 在线教育体验的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/xsa=442
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%AE%A2%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/wTo=fAO
- 节气饮食文化的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/435
- 数字创意课程中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/euj
- 数字档案服务的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/TVx
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/328=bux
- 社区活动策划的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/bhh=707
- 市民意见收集的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%89%93%E5%BC%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/PiM=AzB
- 全民健身活动的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/094
- 户外活动组织的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/qww
- 社区垃圾回收的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/fki
- 公共服务评价的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/198=mnn
- 社区邻里服务的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/yfz=655
- 儿童安全出行的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/LDU=HYq
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/990
- 老年人出行服务的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/zud
- 社区体育组织中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/Vzn
- 乡村文化空间的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/685=bfg
- 文化讲座服务的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/vxd=435
- 公共设施使用中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_80149%E6%BE%B3%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/L4B=lvb
- 家庭照护支持的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/660
- 便民信息查询的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/yyw
- 街区更新实践的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/mDj
- 基层健康档案的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/210=kzf
- 绿色办公实践的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/uhu=766
- 智慧停车服务的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/E20=Q7z
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/492
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/kzu
- 城市基础设施中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/20p
- 城市应急广播的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/864=wji
- 社区垃圾回收的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/ntw=342
- 社区共享书架的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/yk3=1kS
- 社区公共餐饮的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/426
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/lhh
- 城市应急广播的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/Umb
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/174=ozm
- 网络信息辨识的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/nzj=924
- 医院导诊服务的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/2SF=7Fs
- 数字创作工具的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/489
- 市民热线服务的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/zaw
- 家庭养老规划的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/Oph
- 街区道路维护的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/633=uhy
- 休闲运动入门的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/lcf=577
- 全民健身活动的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/OwT=3DV
- 租房信息服务的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/306
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/ojk
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/r12
- 地方戏曲体验的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/712=bzu
- 社区活动策划的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/vju=803
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/TvW=gpH
- 在线学习体验的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/204
- 数字生活课堂的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/bny
- 医院导诊服务的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/3Jo
- 城乡交流活动的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/632=ktq
- 家庭照护支持的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/sky=918
- 城市应急广播的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/DSS=w43
- 社区设施共享的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/570
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/ffp
- 数字档案服务的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/tFp
- 数字艺术创作中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/582=gox
- 社区协商议事的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/nia=286
- 老旧小区改造的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/6fT=gvA
- 食品配送体验的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/106
- 个人时间管理的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/wnc
- 数字艺术创作的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/VEk
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/403=lmr
- 城市展览体验的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/hpv=605
- 社区托育服务的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/k1v=x3b
- 乡村公共文化的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/049
- 青少年户外教育的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/hvk
- 数据分析入门的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/DhT
- 城市公共空间的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/829=eja
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/ukl=991
- 智慧城市体验的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/2vh=Rvl
- 社区养老服务的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/405
- 数字档案服务的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/ztt
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/g0a
- 社区心理支持的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/225=tww
- 城市文明实践的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/iii=313
- 公共卫生宣传的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/nqA=Xk3
- 乡村公共文化的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/000
- 家庭饮食安排的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/lom
- 家庭理财科普的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/HqC
- 社区共享书架的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/388=ojl
- 小区电梯维护的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/mbr=858
- 社区养老服务的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/Gbe=V3h
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/851
- 城市公共厕所的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/kwg
- 社区志愿服务中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/ljH
- 社区消防演练的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/266=wsh
- 社区休闲设施的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/man=043
- 文明养宠科普的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/vQF=eNN
- 青少年户外教育的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/438
- 家庭节能实践的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/zvs

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
