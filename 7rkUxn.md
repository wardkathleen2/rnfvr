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

- 社区活动空间的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/134
- 地方旅游导览的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/qhv
- 社区环保活动的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/53Q
- 数字公共文化的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/579=snz
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/way=918
- 城市公共空间的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/2gz=Axj
- 社区养老服务的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/222
- 城市水环境观察的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/exk
- 社区活动策划的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/9ja
- 信息无障碍体验的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/065=xwg
- 家庭环保行动的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/sba=799
- 城市共享单车的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0vip-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/0zh=AJF
- 环境监测科普的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/056
- 学校体育活动的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/chi
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/Qu0
- 城市文明出行的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/085=kks
- 环境教育课程的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/dfm=448
- 家庭园艺实践的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vip-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/KFi=s2R
- 在线学习体验的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/120
- 数字生活课堂的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/nnr
- 街头绿植养护的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/jqd
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/010=bxs
- 社区菜市场服务的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/fes=252
- 基层医疗预约的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/gtG=m66
- 绿色消费选择的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/022
- 乡村文化空间的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/ews
- 城市空气科普的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/1tJ
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/652=tqi
- 社会体育指导的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/kwt=462
- 农产品品牌传播的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/Fh7=0HL
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/370
- 家庭环保行动的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/cxr
- 家庭照护支持的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/kZ2
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/518=utl
- 城市文化路线的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/omr=051
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/TIv=xVN
- 数字政务体验的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/814
- 小区公共照明的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/oxj
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/wGC
- 应急物资管理的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/026=pbz
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/wsd=414
- 城乡交流活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/Rpr=tpY
- 基层服务创新的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/952
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/ewt
- 街头绿植养护的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/WLT
- 城市可持续生活的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/637=ljo
- 终身学习资源的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/qkv=859
- 社区慢性病防控的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vip-%E9%A6%96%E9%A1%B5_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/7Ik=2rd
- 本地旅行体验的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/568
- 无障碍出行的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/vzc
- 节气饮食文化的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/ym1
- 科普展览体验的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/384=enj
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/vrb=492
- 数字资源检索的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vip-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/LUZ=L4j
- 社区科普课堂的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/492
- 科技馆参观体验的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/cva
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/VPz
- 公共健身器材的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/399=vqd
- 城市基础设施的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/csa=682
- 城市微更新实践的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/2Nz=WG7
- 亲子科普活动的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/498
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/flu
- 家庭志愿活动的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/Dq1
- 文明养宠科普的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/590=fdm
- 社区共享书架的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/dhd=001
- 公共服务咨询的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/Tf8=E9M
- 城市公共厕所的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/316
- 家庭照护支持的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/lbd
- 休闲运动入门中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/tHp
- 药品使用科普的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/592=ueu
- 青年职业探索的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/usc=755
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/R5c=x4H
- 公共空间休憩的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/516
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/mzp
- 安全出行教育的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/12o
- 数字便民地图的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/505=arn
- 乡村产业科普的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/wsj=928
- 城市便民驿站的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/o9Y=BGn
- 居家防滑改造的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/647
- 家庭环保行动的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/qsv
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/Ywo
- 家庭用电安全的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/651=ovs
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/vgq=447
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/SOQ=kWn
- 公园无障碍服务的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/977
- 公共交通接驳的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/lzo
- 家庭饮食安排的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/4nV
- 家庭科学教育的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/589=krx
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/rgj=229
- 基层服务创新的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/uE6=XHr
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/811
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/pof
- 公共服务指南的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/jku
- 社区便利生活的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/868=duy
- 线上办事服务的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/vjt=093
- 街道综合服务的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/uMt=3RL
- 传统节日科普的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/644
- 急救知识普及的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/rvc
- 家庭教育交流中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/q9D
- 生活技能分享的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/482=ywp
- 乡村公共文化的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/eve=678
- 开源技术交流的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/3ot=wSX
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/701
- 数字学习资源的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/pjq
- 亲子阅读活动的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/Ir9
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/211=ecb
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/cak=535
- 社区邻里服务中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/xoI=GXc
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/045
- 数字学习资源的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/kpf
- 社区协商议事的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/Ytl
- 急救知识普及的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/074=jca
- 小区停车协商的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/nrk=569
- 绿色消费选择的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/2Bo=0g3
- 老旧小区改造的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/548
- 数字艺术创作的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/tgf
- 志愿者培训交流的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/ahz
- 社区故事采集的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/925=uqq
- 通勤路线规划的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/qns=956
- 社区互助网络的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/twr=9B4
- 城市慢行系统的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/571
- 科学运动指导中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/xud
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/ns9
- 家庭养老规划的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/207=wyo
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/vby=819
- 市民意见收集的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/yMl=F8Y
- 终身学习资源的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/517
- 公共交通接驳的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/ghs
- 社区托育服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/loL
- 社区防暑服务的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/047=nxx
- 个人数据管理的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/wds=561
- 邻里共享空间的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/ZhH=QBG
- 光伏知识科普的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/541
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/guw
- 城市骑行环境的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/BLV
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/736=mou
- 基层健康档案的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/fqb=231
- 城市运动公园的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/Zql=sY5
- 个人数据管理的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/502
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/gij
- 城市慢行系统的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/7va
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/006=kwm
- 终身学习资源的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/wox=717
- 个人时间管理的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/O30=wBy
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/768
- 文化讲座服务的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/tke
- 就业技能培训的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/b4I
- 传统节日科普的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/857=nzf
- 地方美食文化的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/qqz=600
- 网络信息辨识的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/AEv=bEs
- 绿色建筑理念的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/744
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/gol
- 课后服务体验的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/YBx
- 电动汽车充电的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/103=ehx
- 城市人文观察的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/yth=055
- 城市空气科普的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/7tB=qxC
- 数字资源检索的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/225
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/obk
- 社区家校合作的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/oFr
- 智能家居应用中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/074=pet
- 安全出行教育的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/uqx=473
- 骑行路线规划的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/1bf=KLd
- 数字便民地图的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/229
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/bdj
- 科学观察活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/lnn
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/740=wmn
- 全民健身活动的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/unx=023
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/wGq=pi5
- 青少年户外教育的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/166
- 网络安全教育的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/tzk
- 城市骑行环境的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/Uzx
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/027=hyu
- 乡村文化空间的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/lus=509
- 绿色建筑理念的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/djG=qxl
- 开放式学习空间中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/257
- 气象科普传播的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/ijc
- 儿童户外活动的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/bjp
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/780=uut
- 节约用水实践的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/asx=100
- 社区花园共建的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/hP6=GL5
- 本地历史资料的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/871
- 节约用水实践的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/nxk
- 食品配送体验的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/OaK
- 社区信息发布的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/589=upp
- 数字设备回收的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/pih=069
- 社区绿色空间的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/HZp=JhW
- 街区绿化养护的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/336
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gtt
- 绿色出行服务的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Uv1
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/376=xul
- 公共设施使用的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/lwk=412
- 旧物循环利用的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/meQ=R98
- 老年人出行服务的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/887
- 个人数据管理的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/eyn
- 便民维修服务的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/Xja
- 街区小店体验的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/597=nii
- 环境监测科普的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/qlb=080
- 社区故事采集的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/YAj=EE8
- 青年就业服务的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/355
- 社区商业活力的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/cwh
- 公共设施维护的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/oUx
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/007=nfo
- 数字学习资源的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/rmb=005
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/0Tc=cKv
- 公共服务沟通的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/529
- 便民服务地图的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/wxh
- 城市公共空间的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/3Hn
- 青年就业服务的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/691=nev
- 创业经验分享的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/aal=520
- 绿色消费选择的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/jEc=GMS
- 公益活动组织的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/038
- 租房信息服务中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/tbi
- 社区运动空间的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/bNC
- 机器人科普活动的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/821=lmm
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/qih=827
- 社区菜市场服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/ZZD=93n
- 校园节能行动的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/943
- 租房信息服务的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/hku
- 家庭环保行动的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/3JB
- 社区活动空间的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/693=sim
- 灵活就业交流的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/row=492
- 科普展览体验的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/1gj=3ov
- 社区体育组织的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/305
- 城市生活记录的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/vce
- 公园休闲体验的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/R3G
- 科学信息获取的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/030=iid
- 社区体育组织的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/fgb=137
- 社区文化传播的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/FUt=kjn
- 电动汽车充电的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/069
- 个人信息保护的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/jvp
- 儿童户外活动的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/eKT
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/271=hjh
- 基层健康档案的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/vsb=770
- 公共卫生宣传的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%B9%A6%E7%94%BB?/q3O=Y2Y
- 城市社区治理的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/487
- 街区道路维护的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/uev
- 家庭网络使用的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/6XV
- 物业服务沟通的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/137=osf
- 职业技能学习的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/exs=557
- 社区花园共建的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/4dg=Wfl
- 城市生活服务的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/937
- 城市公共厕所的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/slv
- 课后服务体验的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/Du1
- 乡村生态观察的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/192=ghi
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/zir=434
- 节假日出行安排的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/nBJ=fPy
- 社区便民集市的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/715
- 乡村生态观察的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/peh
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/TBm
- 家庭阅读计划的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/625=klb

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
