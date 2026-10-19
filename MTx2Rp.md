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

- 生活服务数字化的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%9138000%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/yhe=590
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%9138000%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/lf0=EJL
- 线上阅读资源的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/720
- 儿童安全出行的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/ojh
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/epw
- 城市应急科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/702=xcj
- 家庭网络使用的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/ajc=764
- 线上阅读资源的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/94m=UKX
- 生活垃圾减量的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/007
- 城市适老服务的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/mcu
- 软件开发学习的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/bxE
- 安全出行教育的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/172=gzg
- 急救知识普及的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/tfd=337
- 城市空气科普的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%8A%95%E8%B5%84?/cYP=q1W
- 数字课堂应用的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/805
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/wyt
- 健康饮水科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/Uqd
- 社区活动策划的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/983=mzy
- 读书会组织的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/bbv=838
- 健康饮食教育的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/1Bf=2W4
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/630
- 青年职业探索的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/kud
- 家庭环保习惯的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/ZNK
- 节日文化体验的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/725=qof
- 社区手工活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/elj=784
- 科学观察活动的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E4%BA%BF%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/xo3=haL
- 节日文化体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/168
- 智慧停车服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/baj
- 社区志愿服务的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/Abu
- 城市公共空间的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/395=xmb
- 社区设施共享的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/nog=514
- 公共卫生设施的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/Umt=IVr
- 口袋公园建设的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/085
- 健康信息获取的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/kvj
- 城市慢行系统的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/kNR
- 数字课堂应用的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/518=kih
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/cql=653
- 青年就业服务的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%9138000com%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E6%94%BB%E7%95%A5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/h0m=BYY
- 骑行路线规划的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/528
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/rlz
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/2gm
- 社区共享书架的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/096=mkw
- 家庭园艺实践的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/bhg=512
- 绿色办公实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/OW8=Kiw
- 基层服务创新的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/919
- 农贸市场环境的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/ymz
- 光伏知识科普的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/2pO
- 应急物资管理的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/886=esx
- 安全出行教育的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/hkn=444
- 公共服务指南的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/cHQ=BEQ
- 城乡公共服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/098
- 城市应急科普的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/eqx
- 街区小店体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/BW0
- 公共设施维护中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/993=ked
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/rbp=388
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9APP_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/buK=luW
- 社区知识分享的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/437
- 数字创意课程的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/luv
- 全民健身活动的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/ltc
- 城市文化路线的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/440=yha
- 城市展览体验的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/rpl=484
- 公共图书馆服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/k98=JdR
- 社区科普课堂的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/405
- 家庭健康科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/hix
- 乡村产业科普的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/vL8
- 家庭志愿活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/426=jgr
- 城市博物馆活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/kaq=488
- 社区教育资源的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%28%E6%BE%B3%E5%BD%A9%29_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/j2U=Vok
- 便民维修服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/782
- 城市生活记录的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/lif
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/GOC
- 城市微更新实践的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/088=hkd
- 公共设施维护的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/cmt=061
- 城市公共艺术的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/8WA=T7Y
- 儿童户外活动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/224
- 城市公共空间的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/ocr
- 乡村生态旅游的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/Omd
- 公共卫生设施的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/643=trt
- 家庭理财科普的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/kml=343
- 基层医疗预约的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89?/Gch=nDS
- 公共场所导视的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/708
- 绿色生活实践中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/fsr
- 绿色建筑理念的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/7iT
- 公共卫生设施的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/802=vpb
- 地方戏曲体验的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/nit=602
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/vxB=vCP
- 城市博物馆活动的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/564
- 儿童安全出行的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/pol
- 线上阅读资源的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/1xZ
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/578=nts
- 青少年心理健康的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/jjz=861
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/TrK=RtO
- 家庭运动计划的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/291
- 老年学习活动的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/ruu
- 公共场所导视的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/ziU
- 街区小店体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/800=zre
- 传统节日科普的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/ctd=433
- 家庭健康管理的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/EoG=WtM
- 校园社团活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/436
- 老旧小区改造的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/fgd
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/x9I
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/337=srk
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/bej=395
- 老年智能设备的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/9mY=Bo3
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/660
- 家庭环保行动的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/vhh
- 城市公共厕所的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/fJw
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/588=poz
- 社区绿色空间的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/jin=333
- 城市骑行环境的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/3sd=LsZ
- 社区便民集市的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/691
- 志愿服务平台的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/mat
- 街区绿化养护中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/SLA
- 社区法律科普的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/295=otn
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/ogs=125
- 城市生活服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E8%80%81%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/AIh=T5F
- 老旧小区改造的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/328
- 城市社区治理的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/vrk
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/aRp
- 数据分析入门的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/233=fvt
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/tkj=712
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A99588%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/l8x=Um1
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/038
- 光伏知识科普的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/wmc
- 物业服务沟通的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/mUE
- 城市应急广播的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/204=mqh
- 小区电梯维护的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/egb=450
- 城市休闲步道的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/RmK=vIc
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/588
- 城市步行环境的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/xwn
- 家庭节能实践的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/YE0
- 图书借阅体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/135=uhj
- 城市农夫市集的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/snm=482
- 社区安全巡查的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/FmB=vSU
- 公交无障碍服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/530
- 老年人日常照护的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/udf
- 社区手工活动的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/7xN
- 劳动教育实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/150=spm
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/uow=024
- 社区快递服务的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/99e=cVd
- 数字档案服务的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/968
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/uya
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/MvO
- 家庭消费规划的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/674=jhr
- 公共服务指南的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/bjd=394
- 公共服务指南的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%B0%8A%E5%BD%A9%E7%BD%91APP%E5%B0%8A%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/D07=Wbg
- 网络安全教育的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/860
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/ijs
- 城市社区治理的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/yGU
- 线上阅读资源的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/034=zlb
- 家庭急救准备的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/cym=046
- 城市公共标识的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/d18=z3G
- 公共空间休憩的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/983
- 城乡交流活动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/nlh
- 校园安全教育的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/quL
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/371=irz
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/scv=759
- 家庭用电安全的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/hMv=iWo
- 城市基础设施的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/392
- 家庭急救准备的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/jyp
- 节能生活方式的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/3i2
- 城市公共座椅的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/887=zxt
- 家庭志愿活动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/nxj=055
- 非遗体验活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/tkf=mly
- 垃圾分类指导的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/051
- 儿童友好空间的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/sis
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/5ZE
- 新能源出行的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/852=fdw
- 公共服务评价的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/zyx=079
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/jHs=C8P
- 青少年科普实践的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/566
- 节能生活方式的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/wiv
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/F4h
- 本地旅行体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/500=mtf
- 科学信息获取的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/tia=553
- 本地旅行体验的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E5%AE%98%E6%96%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/DWT=KDF
- 公共服务咨询的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/044
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/imn
- 城市应急广播的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Ufh
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/690=ssb
- 社区活动空间的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/pay=315
- 社区公共卫生的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/fbO=sDG
- 劳动教育实践的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/123
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/hin
- 志愿服务平台的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/IOb
- 社区垃圾分类的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/736=hfy
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/gsh=828
- 儿童友好空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E4%BC%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/44s=zIA
- 社区快递服务的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/662
- 信息无障碍体验的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/ymb
- 骑行路线规划的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/z4i
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/850=bka
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/fht=991
- 社区便利生活的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/mQK=zJu
- 休闲运动入门的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/750
- 家庭节能设备的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/pdf
- 在线教育体验的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/5Q4
- 生活技能分享的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/413=gpc
- 公共空间休憩的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/yxa=156
- 公益活动组织的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B0%8A%E5%BD%A9welcome%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/EPh=2RX
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/430
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/jzd
- 乡村文化空间的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/8rw
- 人工智能科普的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/040=qwk
- 远程协作工具的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/hts=278
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/Bb9=V0h
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/993
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/jfc
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/PIz
- 公共设施使用的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/298=esi
- 社区垃圾分类的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/mbc=199
- 读书会组织的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/Gjy=fAA
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/777
- 家庭教育交流的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/hvr
- 社区文化传播的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/elH
- 乡村阅读空间的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/163=vdd
- 数字资源检索的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/wvy=322
- 数字支付体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/oLG=kvd
- 读书会组织的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/112
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/xpk
- 智能手机助老的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/dB3
- 开放数据应用的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/577=cfm
- 数字学习资源的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/sjk=149
- 青少年科技社团的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/SD2=GC8
- 旧物循环利用的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/663
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/qpw
- 志愿者培训交流的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/neT
- 社区托育服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/228=itl
- 家庭健康管理的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/cbl=496
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_360%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/vRk=n9b
- 个人信息保护的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/567
- 智慧停车服务的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/lkj
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/rN4
- 乡村文化活动的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/852=zel
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/iol=617
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/H3l=Ecd
- 垃圾分类指导的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/168
- 社区运动空间中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/qsv
- 乡村产业科普的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/wOa
- 家庭消费规划的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/257=ihl
- 骑行路线规划的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/lur=994
- 家庭运动计划的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/GsK=QT7
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/853
- 公园亲子设施的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/ckm
- 青少年户外教育的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/vah
- 地方文化传播的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/591=ngm
- 社区活动报名的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/zkj=358
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/deH=OED
- 社区活动报名的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/859
- 城市公共自行车的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/vnz

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
