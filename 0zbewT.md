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

- 社区托育服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/byo=337
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/j7H=nqH
- 社区知识分享的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/577
- 远程协作工具的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/anb
- 社区科普课堂的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/5L7
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/807=mzt
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/dss=837
- 智慧停车服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%96%B0%E7%94%A8%E6%88%B7%E5%BD%A9%E9%87%9138%E5%85%83%E4%BD%93%E8%82%B2_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/AbJ=rFU
- 公共文化活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/382
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/smp
- 地方文化传播的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/eor
- 公共设施维护的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/585=wdh
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/bpz=542
- 社区庭院绿化的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/uWB=qXQ
- 城市适老服务的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/785
- 农村环境治理的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/dzk
- 地方美食文化的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/Q4Z
- 社区快递服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/840=djv
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/iik=946
- 家庭养老规划的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E6%8F%90%E5%89%8D50%E7%A7%92%E7%9C%8B%E7%BB%93%E6%9E%9C_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/Y4d=8te
- 市民意见收集的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/935
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/xpi
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/wFI
- 城市夜间照明中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/853=hle
- 城市空气科普的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/jjt=316
- 市民热线服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/Jp5=xGO
- 社区防暑服务的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/992
- 社区防暑服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/hov
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/CzO
- 创业经验分享的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/717=wzg
- 公共交通信息服务的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/izk=515
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/99v=QL0
- 地方文化传播的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/329
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/ejj
- 医院导诊服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/iMq
- 小区停车协商的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/466=enz
- 邻里互助活动的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/sqg=974
- 公共设施维护的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91VIII%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/UiD=v2F
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/104
- 社区生活指南的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/zul
- 绿色办公实践中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/oOR
- 公共服务预约的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/983=ddm
- 社区读书角建设的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/xvz=157
- 城市社区治理的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/Vxu=VTM
- 社区养老服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/441
- 城市水环境观察的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/yts
- 儿童友好空间的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/wA1
- 公交无障碍服务的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/710=ivb
- 网络信息辨识的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/vje=419
- 市民意见收集的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/A5g=K35
- 垃圾分类指导的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/796
- 网络安全教育的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/fmv
- 社区运动空间的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/c97
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/568=ngc
- 公共场所导视的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/jak=479
- 公共空间休憩的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/yQL=LGj
- 非遗课堂体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/719
- 青少年科技社团的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/rmz
- 城市住房服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/GnI
- 农贸市场环境的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/266=kuu
- 公共设施使用的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/wjj=592
- 食品安全科普的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/QFh=hVB
- 家庭教育交流的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/097
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/men
- 数字阅读服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/IUl
- 城市公共座椅的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/568=sjq
- 城市应急科普的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/bia=943
- 社区生活指南的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/FyY=Syw
- 健康步道使用的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/659
- 文明养宠科普中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/gyh
- 青少年心理健康的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/J6c
- 社区阅读服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/491=pwt
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/tze=380
- 生活垃圾减量的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/JWQ=0sO
- 急救知识普及的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/544
- 公共健身器材的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/wgr
- 城乡交流活动的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/nf5
- 街区道路维护的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/895=ksb
- 社区休闲设施的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/gwx=731
- 数字支付体验的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/ccx=moU
- 街区更新实践中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/640
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/jcm
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/X8l
- 城市共享单车的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/869=gbx
- 城乡交流活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/yvl=206
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/qzu=3S1
- 城市共享单车的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/645
- 家庭志愿活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/tek
- 老旧小区改造的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/p64
- 数字公共文化的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/854=kmn
- 数字资源检索的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/cta=621
- 城市生活服务的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/3AE=5dz
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/844
- 读书会组织的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/gai
- 社区设施共享的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/w2Q
- 老年人日常照护的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/472=vxy
- 休闲运动入门的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/ict=312
- 食品安全科普的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90?/w3E=MjT
- 社区互助网络的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/913
- 校园阅读活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/ldt
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/oW9
- 社区便民服务的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/260=bgy
- 学校体育活动的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/syy=060
- 乡村文化空间的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/gcq=O56
- 城市骑行环境的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/604
- 数字创意课程的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/dnp
- 数字便民地图的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/ZeP
- 地方民俗记录的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/606=xtt
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/zhv=312
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA?/SIq=Ka6
- 社区读书角建设的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/364
- 社会体育指导的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/gsb
- 社区修缮行动的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/uoT
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/180=syr
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/ojd=011
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/Xe4=314
- 药品使用科普的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/229
- 节能生活方式的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/cqp
- 社区家校合作的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/OnP
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/972=mul
- 节假日出行安排的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/god=550
- 网络安全教育的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8app_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/rnh=cEz
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/611
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/chr
- 邻里共享空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/97z
- 机器人科普活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/499=bdo
- 城市基础设施的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/nmn=663
- 环境监测科普的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Rta=wna
- 城市夜间照明的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/979
- 社区设施共享的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/gqk
- 安全出行教育的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/3TK
- 公共服务沟通的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/080=aem
- 数字政务体验的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/iga=554
- 便民服务窗口的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/RpF=owK
- 市民热线服务的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/400
- 社区应急准备的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/rxz
- 新能源知识普及的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/wiz
- 校园社团活动的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/627=oab
- 非遗体验活动中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/uds=429
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/sDr=W6D
- 网络信息辨识的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/115
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/fbu
- 开放式学习空间的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/i20
- 小区公共照明的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/028=vtv
- 社区活动空间的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/wrq=558
- 节气饮食文化的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/6Qi=1vR
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/350
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/aaf
- 家庭食品保存的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/xr7
- 节约用水实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/244=ehp
- 社区养老服务的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/qca=768
- 运动安全知识的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/KiD=XMT
- 儿童友好空间的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/583
- 公园无障碍服务的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/wbs
- 公共文化活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/Aas
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/310=ftf
- 社区教育资源的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/adw=729
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/4wJ=FRZ
- 数字便民地图的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/963
- 社区公共卫生的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/yml
- 社区养老服务的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/G4J
- 老年学习活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/370=ebq
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/pen=008
- 人工智能科普的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/0bS=MpR
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/684
- 基层健康档案的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kbj
- 家庭急救准备的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/T9b
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/503=ilo
- 家庭安全提示的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zfu=175
- 城市体育设施的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0Nb=VOZ
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/168
- 家庭科学教育的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/uel
- 消防知识宣传的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/O2U
- 社区科普课堂的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/007=xsb
- 老年友好服务的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/ujk=189
- 城市基础设施的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/1wp=KcM
- 社区法律科普中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/912
- 居民健康教育的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/kne
- 运动安全知识的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/fsM
- 数字支付体验的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/353=sqg
- 物业服务沟通的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/osl=912
- 城市可持续生活的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/Oua=Dh9
- 志愿服务平台的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/027
- 乡村生态观察的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/awh
- 公共图书馆服务的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/hiJ
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/682=taf
- 科普展览体验的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/fju=581
- 社区故事采集的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/r3Y=ZVN
- 公共服务沟通的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/425
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/cyl
- 城市夜间生活的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/ejO
- 青少年科普实践的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/321=ifs
- 线上阅读资源的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/mrp=645
- 数据分析入门的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/EAb=Ksd
- 城市展览体验的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/552
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/uln
- 城市步行友好中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/utR
- 家庭理财科普的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/097=alc
- 青少年科技社团的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/ehz=894
- 公共服务指南的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/MQ9=ivr
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/330
- 公共卫生宣传的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/emm
- 口袋公园建设的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/oMA
- 新能源知识普及的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/173=usz
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/cbd=359
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/rK9=5Qm
- 街头绿植养护的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/817
- 城市夜间照明的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/szx
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/7PE
- 邻里互助活动的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/736=yws
- 数字支付体验的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/goa=928
- 小区公共照明的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E8%B1%86%E7%93%A3%E5%88%8A%E7%99%BB?/18X=WQq
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/648
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/dyc
- 健康饮食教育中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/HYl
- 社区宠物管理的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/778=bsq
- 社区协商议事的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/ioc=864
- 社区便民服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_360%E6%99%9A%E6%8A%A5?/ERY=HRC
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/142
- 社区环保活动的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/wye
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/3hD
- 城市噪声观察的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/110=zgp
- 城市展览体验的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/bzx=083
- 街头绿植养护的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/FmV=mo1
- 邻里互助活动的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/355
- 校园安全教育的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/qzz
- 社区运动空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/dvl
- 青少年心理健康的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/131=eko
- 信息无障碍体验的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/hpp=028
- 旧物循环利用的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/Ru4=d1Q
- 农业科普体验的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/982
- 绿色办公实践的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/jyy
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/0ul
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/785=buc
- 文明养宠科普的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/tbi=424
- 小微企业服务的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/dsm=igT
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/380
- 家庭节能实践的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/hej
- 乡村文化活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/SwR
- 网络信息辨识的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/622=ypb
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/ifg=203
- 城市可持续生活的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_360%E5%9C%88%E5%AD%90?/X0y=9jA
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/479
- 公共空间休憩的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/owu
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/Vva
- 科技馆参观体验的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/425=qyx
- 城市基础设施中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/rmw=603
- 城乡公共服务的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/V9R=2Qp
- 传统手工艺体验的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/564
- 公共设施维护的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/nsz

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
