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

- 儿童友好空间的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8yzcpios%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/mCr
- 城乡交流活动的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8yzcpios%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/196=rtk
- 科学运动指导的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8yzcpios%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/duc=997
- 在线教育体验的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8yzcpios%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/EzU=1Uq
- 社区法律科普中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/461
- 家庭用电安全的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/mrz
- 便民信息查询的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/hWw
- 家庭理财科普的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/034=qnm
- 社区托育服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/ics=144
- 公共文化活动的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_49%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/QEo=jja
- 社区心理支持的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/040
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/quf
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/HnO
- 健康信息获取的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/118=zvn
- 邻里互助活动的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/dui=682
- 本地消费场景的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%80%81%E7%89%88106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%88%BF%E4%BA%A7?/kun=NMC
- 社区花园共建的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/328
- 数字设备回收的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/mjg
- 家庭消费规划的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/C0n
- 社区托育服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/830=liz
- 城市微更新实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/esj=796
- 文化场馆预约的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_105%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/jUc=EDr
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/126
- 社会体育指导的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/aya
- 生成式工具使用的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/lE7
- 社区公共卫生的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/599=jxy
- 儿童友好空间的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/pds=349
- 公共设施使用的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1288%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/i18=Tk4
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/090
- 社区宠物管理的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/oez
- 科学教育活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/0Pr
- 数字档案服务的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/967=odr
- 老年人文化生活的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/cen=631
- 电动汽车充电的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F?/In6=26M
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/180
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/eim
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/m6K
- 家庭安全提示的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/649=iwm
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/qlf=908
- 网络安全教育的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/Pzk=SjA
- 公共服务预约的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/557
- 社区快递服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/pji
- 乡村公共文化的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/i5S
- 儿童友好空间的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/204=tuj
- 终身学习资源的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/gmj=196
- 绿色出行服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%90%84%E7%A7%8D%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/EZo=82K
- 数字生活课堂的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/981
- 社区知识分享的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/hcq
- 劳动教育实践的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/dB4
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/290=ary
- 老年人日常照护的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/nog=478
- 城市运动公园的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/Bz9=ppt
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/128
- 文化场馆预约的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/yel
- 数字艺术创作的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/lvq
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/538=hcj
- 休闲运动入门的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/xlb=573
- 社区活动策划的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/6it=o92
- 城市共享单车的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/516
- 网络安全教育的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/xha
- 城市展览体验的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/DtY
- 家庭运动计划的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/463=esb
- 家庭安全提示的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/ocd=719
- 非遗课堂体验的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/omf=w6e
- 社区垃圾回收的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/466
- 农村环境治理的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/ewa
- 数字公共文化中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/erU
- 学校体育活动的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/219=gaa
- 乡村生活观察的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/ufs=347
- 公共设施使用的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/JQt=3mf
- 新能源出行的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/997
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/xxr
- 学校食育活动的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/f4E
- 地方民俗记录的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/410=cqf
- 城市展览体验的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/crm=691
- 公共卫生设施的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%BF%AB8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/gee=A5E
- 乡村产业科普的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/319
- 急救知识普及的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/nfh
- 信息无障碍体验的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/HIY
- 公共空间安全的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/861=lej
- 小区公共照明的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/vqu=906
- 个人数据管理的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/mNH=p8s
- 城市步行环境的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/014
- 线上阅读资源的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/frc
- 运动安全知识的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/uTk
- 城市运动公园的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/608=mgg
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/ldf=756
- 数字档案服务的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/sP5=ils
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/106
- 城市基础设施的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/xdz
- 数据分析入门的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/rEs
- 租房信息服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/203=fud
- 全民健身活动的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/yjr=762
- 在线教育体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88%E6%9C%ACapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/Vf6=MP4
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/141
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/stx
- 光伏知识科普的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/E6g
- 文化讲座服务的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/502=tuw
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/rar=475
- 光伏知识科普的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/Oq8=THi
- 社区科普课堂的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/813
- 校园社团活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/bax
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/7H7
- 城市文明实践的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/742=lav
- 骑行路线规划的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/kxt=854
- 生活服务数字化的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/anq=nmx
- 老年学习活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/783
- 学校体育活动的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/fjv
- 校园节能行动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/Syc
- 城市人文观察的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/774=yrp
- 物业服务沟通的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/mgv=389
- 光伏知识科普的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/jtf=3mS
- 老年人文化生活的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/974
- 基层健康档案的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/mcx
- 社区邻里服务的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/9Tt
- 非遗体验活动的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/363=mar
- 旧物循环利用的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/fwh=590
- 家庭安全提示的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/fTg=lu3
- 社区互助网络的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/596
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/nsb
- 亲子科普活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/DJ9
- 消防知识宣传的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/575=aoc
- 市民意见收集的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/pbe=256
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/1h6=T7t
- 光伏知识科普的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/340
- 数字支付体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/azp
- 城市树木认养的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/bIK
- 公共交通信息服务的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/665=hiz
- 户外活动组织的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/dfj=232
- 社区科普课堂的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%85%AD%E5%88%86%E5%BD%A9%E7%A5%A86F99APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/YyM=7GT
- 城市社区治理的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/259
- 社区手工活动的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/han
- 街区小店体验的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/qzv
- 城市文明出行的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/668=jbt
- 公交站点体验的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/fap=709
- 家庭消费规划的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A81.0_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/8fp=wL6
- 数字学习资源的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/846
- 健康信息获取的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/yvw
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/Rv4
- 老年数字阅读的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/801=dza
- 街区道路维护的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/axp=240
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AD%A6%E5%BA%9C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/oBU=roO
- 绿色出行服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/225
- 城乡交流活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/ijs
- 社区公共卫生的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/ppN
- 老年学习活动的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/573=tqz
- 乡村阅读活动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/wtu=329
- 文明养宠科普的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1988%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/nRC=UMC
- 社区科普课堂的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/842
- 科学信息获取的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/pgu
- 小区停车协商的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/Qs5
- 老年智能设备的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/683=hdz
- 社会体育指导的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ouu=565
- 公共健身器材的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_ios500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/rm6=mLJ
- 电动汽车充电的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/927
- 家庭安全提示中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/ldd
- 城乡公共服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/7rN
- 社区故事采集的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/745=xfu
- 数字资源检索的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/lwc=399
- 社区商业活力的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/beU=wvr
- 乡村公共阅读的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/071
- 智能家居应用的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/tus
- 地方旅游导览的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/3Gh
- 城市骑行环境的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/409=zmb
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/plx=555
- 农业科普体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/pCp=8za
- 乡村文化空间的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/252
- 机器人科普活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/bno
- 公共服务数字化的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/7C7
- 社区体育组织的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/428=gjf
- 社区共享书架的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/gnn=746
- 数字学习资源的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/9Wx=PLD
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/589
- 志愿服务平台的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/ucv
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/KRC
- 数字政务体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/098=mns
- 社区活动空间的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/mpu=203
- 城市住房服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/C5Y=44N
- 社区商业活力的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/848
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/xgs
- 线上阅读资源中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/L0p
- 灵活就业交流的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/700=rsf
- 老年人出行服务的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/kms=946
- 在线学习体验的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/yoR=umQ
- 社区活动策划的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/457
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/fca
- 社区共享书架的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/iTT
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/233=dsl
- 街头绿植养护的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/pie=600
- 城市公共标识的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/g4H=07k
- 校园节能行动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/181
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/vwn
- 公共场所导视的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/4D9
- 社区养老服务的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/492=ncy
- 全民健身活动的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/vpv=622
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/rXX=vib
- 家庭志愿活动的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/179
- 本地消费场景的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/drq
- 科学观察活动的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/9Sk
- 城市空气科普的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/643=idh
- 科技馆参观体验的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/pex=893
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/Kr2=FCq
- 社区老年食堂的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/570
- 社区共享书架的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/lho
- 生活技能分享的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/Xjf
- 无障碍信息设计的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/553=yva
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/tdl=380
- 个人数据管理的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/cUs=Ijo
- 远程协作工具的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/315
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/cgx
- 老年运动活动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/o3D
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/925=xmy
- 节气饮食文化的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/nwg=743
- 人工智能科普的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/Wyt=sAr
- 地方民俗记录的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/797
- 家庭教育交流的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/jiv
- 城市文明出行的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/YEq
- 家庭健康管理的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/602=ndj
- 传统节日科普的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/aml=860
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/EYm=rCH
- 社区信息发布的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/067
- 数字素养提升的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/svo
- 创业经验分享的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/x65
- 社区生活指南的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/576=iuo
- 食品安全科普的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/lrk=284
- 线上办事服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/2bh=Pe5
- 公共设施使用中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/463
- 公共服务咨询的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/zxw
- 居民健康教育的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/A2P
- 城市夜间照明的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/235=vee
- 社区便民服务的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/lkz=153
- 无障碍出行的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/Vje=RsG
- 社区协商议事的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/288
- 地方戏曲体验的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/bzq
- 社区体育组织的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/GvS
- 地方民俗记录的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/905=xly
- 城市公共座椅的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/peb=183
- 公共场所导视的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/NkI=x72
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/186
- 邻里互助活动的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/jqx
- 城市游园体验的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/17O
- 绿色校园实践的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/690=aso
- 城市水环境观察的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/fah=136
- 社区活动策划的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/30h=xgS
- 乡村产业科普的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/458
- 环境监测科普的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/kok
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/r95
- 社区法律科普的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/256=vzj
- 全民健身活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/apg=934
- 全民阅读推广的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/GmE=7NO

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
