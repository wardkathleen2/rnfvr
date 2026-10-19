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

- 社区体育组织的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_vip%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/clc=133
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_vip%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/0My=YCl
- 数字素养提升的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/307
- 公共服务数字化的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/clm
- 城市应急科普的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/mlD
- 城市游园体验的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/961=fvu
- 机器人科普活动的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/jxv=913
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/ueh=qdk
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/831
- 街区绿化养护中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/qno
- 社区协商议事的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/ghi
- 城市公共座椅的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/605=iiy
- 公共健身器材的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/jfv=749
- 食品安全科普的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/r7o=mdl
- 科学健身方法的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/790
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/hig
- 城市步行友好中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/aYV
- 科学观察活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/008=qnn
- 校园社团活动的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/pln=263
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/LcV=Asl
- 亲子科普活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/449
- 城市住房服务的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/dbu
- 科学信息获取的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/f4M
- 开源技术交流的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/478=fga
- 科学运动指导的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/qcc=707
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/r7q=45e
- 社区家校合作中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/368
- 图书馆数字服务的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/wgg
- 低碳社区实践的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/qZ5
- 社区老年食堂的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/397=mzh
- 社区慢性病防控的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/wge=088
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_56%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%98%E7%82%B9?/bag=emi
- 公共空间照明的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/572
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/lea
- 社区文化节活动的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/jjm
- 节能家电使用的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/625=yhl
- 公共场馆服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/upr=463
- 家庭安全提示的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_56%E5%BD%A9%E7%A5%A8-welcome_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/D7V=HdB
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/635
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/ocz
- 社区便利生活的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/jlH
- 社区养老服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/810=ppo
- 城市公共饮水的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/nor=592
- 生活技能分享的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_56%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/LBh=wdz
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/034
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/jfj
- 社区知识分享的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/F8C
- 老年数字阅读中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/093=fup
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/yus=390
- 社区艺术活动的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/EMO=WkG
- 基层医疗预约中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/011
- 社区交通安全的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/wjm
- 骑行路线规划的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/t6O
- 数字创意课程的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/755=kat
- 社区家政服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/wtu=489
- 社区活动策划的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A858%E7%BD%91%E6%8A%95_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/hiS=jGB
- 乡村阅读空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/234
- 农村环境治理的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/twb
- 应急物资管理的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/j8r
- 社区法律科普的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/646=vlc
- 节日文化体验的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/xhz=993
- 数字素养提升的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/t4U=bW7
- 节日文化体验的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/878
- 公交无障碍服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/you
- 社区心理支持的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/beZ
- 社区故事采集的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/140=dsx
- 绿色办公实践的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/eme=356
- 社区修缮行动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A32023%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/z9y=yTD
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/153
- 社会体育指导的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/guj
- 环境教育课程的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/rNe
- 城市农夫市集的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/091=oba
- 城市应急科普的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/kaj=557
- 社区宠物管理的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/zqg=jO1
- 社区文化节活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/917
- 老年友好服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/adp
- 基层健康服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/S0f
- 灵活就业交流的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/149=oib
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/dmb=989
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8668%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/Ktx=pnf
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/069
- 骑行路线规划的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/ezi
- 物业服务沟通中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/yQy
- 城市文化路线的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/171=gic
- 城市基础设施中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/okh=867
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_668%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/3rr=TJm
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/932
- 健康饮食教育的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/hns
- 地方文化传播的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/RpV
- 青年职业探索的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/223=dmb
- 老年运动活动的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/krx=188
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8668%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/JDK=hIL
- 环境监测科普的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/245
- 机器人科普活动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/kzt
- 机器人科普活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/6Ff
- 健康饮水科普的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/014=azv
- 城市公共标识的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/wzm=436
- 社区活动报名的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_668%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/aXm=0B6
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/108
- 社区托育服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/rsd
- 街头绿植养护的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/ojP
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/944=gwh
- 智能手机助老的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/pcb=362
- 公共空间安全的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/iic=dZZ
- 便民服务地图的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/503
- 公共服务数字化的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/dwp
- 家庭节能实践的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/ZzS
- 城市可持续生活的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/891=nft
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/naq=824
- 校园安全教育的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/jbK=2aA
- 家庭节能实践的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/235
- 儿童安全出行的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/egk
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/AzS
- 创业经验分享的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/156=myz
- 老旧小区改造的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/qau=718
- 科学健身方法的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_829%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/hpz=K0T
- 社区法律科普中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/290
- 科学健身方法的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/qok
- 绿色办公实践的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/DMd
- 通勤路线规划的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/177=sai
- 软件开发学习的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/pzs=031
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/t1I=fqY
- 线上办事服务的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/097
- 家庭节能设备的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/ftd
- 骑行路线规划的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/TLz
- 社区修缮行动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/412=fmh
- 基层健康服务的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/aaq=598
- 社区安全巡查的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/0M8=4B1
- 光伏知识科普的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/756
- 城市绿道建设的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/dac
- 电动汽车充电的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/xHh
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/312=lqg
- 数字政务体验的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/tvk=614
- 公交站点体验的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/hkX=n4G
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/439
- 社区垃圾回收的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/xah
- 街区小店体验的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/RS7
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/123=xxi
- 城乡公共服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/orf=083
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/MUm=Tf2
- 城市游园体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/445
- 休闲运动入门的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/zvh
- 城市农夫市集的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/5SD
- 户外活动组织的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/371=dnq
- 开放式学习空间的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/ffr=813
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_8886%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/lMA=mbd
- 老年智能设备的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/632
- 老年人文化生活的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/zdd
- 老年学习活动的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/sBB
- 远程协作工具的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/768=dqh
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/gep=103
- 社区绿色空间的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8886%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/PLt=Jir
- 社区快递服务的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/847
- 城市公共标识的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/hlm
- 职业技能学习的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/7k1
- 垃圾分类指导的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/596=hsv
- 社区读书角建设的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/iyy=557
- 城市公共自行车的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_8886%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/Z3l=3FS
- 公共空间安全的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/698
- 无障碍出行的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/ats
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/lrn
- 城市地名文化的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/576=fts
- 老年数字阅读的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/slz=726
- 社区科普课堂的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_8886%E5%BD%A9ios_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/OFM=6HX
- 生成式工具使用的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/799
- 社区老年食堂的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/hfv
- 公园休闲体验的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/ywb
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/034=epv
- 人工智能科普的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/vut=889
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_8886%E5%BD%A9-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/GSO=u0G
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/769
- 公园亲子设施的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cec
- 城市基础设施的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/E1B
- 便民信息查询的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/671=hsz
- 家庭教育交流的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gak=634
- 图书借阅体验的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_8886%E5%BD%A9-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/1Ez=AiJ
- 社区家校合作的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/850
- 街区小店体验的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/qvb
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/psI
- 节约用水实践的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/534=aoc
- 消防知识宣传的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/zag=083
- 数字档案服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8886%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/CgU=Sav
- 社区公共卫生的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/080
- 校园安全教育的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/jsc
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/FjA
- 应急物资管理的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/976=xcp
- 城乡公共服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/yrh=435
- 社区商业活力的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_95%E5%BD%A9%E7%A5%A8%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/QVs=bbY
- 社区托育服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/245
- 家庭收纳实践的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/szj
- 社区便民服务的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/VZ3
- 青年就业服务的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/948=oec
- 急救知识普及的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/rke=889
- 本地旅行体验的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8_%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/eTo=N8f
- 公共场所导视的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/129
- 社区商业活力的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/qic
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/V1r
- 科学健身方法的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/420=lrj
- 老年智能设备的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/sba=181
- 青年就业服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/KGg=FPE
- 家庭收纳实践的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/660
- 乡村生态观察的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/gmi
- 乡村教育资源的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/pNw
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/259=eev
- 基层医疗预约的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/ygz=144
- 社区公共卫生的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/K6o=nnL
- 通勤路线规划的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/684
- 社区健康讲座的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/sob
- 社区共享书架的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/gYK
- 社区公共议事的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/469=mvo
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/plh=308
- 城市绿色交通的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_App%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/Jg3=CkM
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/662
- 家庭食品保存的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/yuz
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/ZGi
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/365=uen
- 城市绿色交通的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/sdx=688
- 街区道路维护中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_TT%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/8ux=uii
- 家庭健康科普中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/580
- 邻里共享空间的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/blr
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/0zf
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/112=ttq
- 学校体育活动的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/sfu=087
- 社区便民集市的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_TT%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/PYe=7Uw
- 乡村公共阅读的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/366
- 家庭用电安全的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/dmq
- 城市可持续生活的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/QyT
- 城市应急科普的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/731=whq
- 社区快递服务的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/wsg=638
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_tt%E5%BD%A9%E4%B8%80%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/Hqo=Go3
- 社区读书角建设的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/636
- 家庭养老规划的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/wtb
- 城市住房服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/Kji
- 社区防暑服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/658=gdf
- 非遗体验活动的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/ktp=706
- 数字创作工具的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/uGm=yLY
- 租房信息服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/490
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/kux
- 节能家电使用的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/KhC
- 城市展览体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/949=wwu
- 家庭照护支持的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/qas=039
- 线上办事服务的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/Z9Z=B1c
- 全民健身活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/912
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/nbp
- 本地旅行体验的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/r5w
- 社区生活指南的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/399=kcq
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/pbn=844
- 城市住房服务的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/WFr=bWC
- 数字创意课程的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/935
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zlm

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
