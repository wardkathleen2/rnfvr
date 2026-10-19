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

- 家庭急救准备的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/uku=115
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/J9h=dGs
- 图书馆数字服务的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/843
- 小区电梯维护的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/sge
- 社区生活指南的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/Hov
- 个人时间管理的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/558=zyy
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/ojr=538
- 校园社团活动的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/oJe=ldM
- 儿童户外活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/335
- 城市骑行环境的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/zom
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/lmp
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/720=gmv
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/ikr=563
- 科学健身方法的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/wLQ=OX8
- 地方民俗记录的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/592
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/wyb
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/ItY
- 家庭运动计划的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/700=cvi
- 社区宠物管理的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/wmh=469
- 数字设备回收的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/gmh=9fy
- 急救知识普及的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/632
- 城市便民驿站的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/kxp
- 儿童友好空间的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/aDr
- 青年职业探索的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/433=kzu
- 社区修缮行动的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/ntf=984
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/6m2=KoI
- 志愿者培训交流的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/414
- 社区菜市场服务的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/ozb
- 公共场所导视的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/VcF
- 校园安全教育的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/660=skd
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/lyc=155
- 老年友好服务的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/Kng=Tai
- 科学运动指导的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/877
- 绿色办公实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/jdb
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/7eu
- 家庭园艺实践的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/034=bnz
- 消防知识宣传的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/lav=470
- 城市公共标识的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/ccd=hxw
- 数字素养提升的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/074
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/dre
- 社区活动空间的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/lsS
- 社区读书角建设的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/345=aeg
- 城市步行环境的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/fgo=990
- 低碳社区实践的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/dWO=h4T
- 网络安全教育的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/116
- 校园阅读活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/wkm
- 便民信息查询的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/QD2
- 老年友好服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/132=mxn
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/hfg=589
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/yTi=nqW
- 农贸市场环境的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/989
- 家庭健康科普的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/scy
- 个人时间管理的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/6Fh
- 科学信息获取的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/749=wqm
- 城市应急广播的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/uoy=809
- 生成式工具使用的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/K8w=aNw
- 节气饮食文化中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/252
- 课后服务体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/qxf
- 健康饮水科普的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/cQS
- 公共场所导视的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/974=smi
- 家庭理财科普的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/gkx=650
- 健康信息获取的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/f0b=bry
- 居家适老化改造的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/591
- 儿童户外活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/trf
- 老年人文化生活的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/5Tt
- 乡村公共服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/778=bxo
- 数字档案服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/rxh=410
- 社区健康讲座的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/SxI=FSo
- 社区学习活动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/260
- 数字档案服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/ujz
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/ruS
- 街区道路维护的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/358=zgm
- 城市可持续生活的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/jsx=746
- 小微企业服务的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/gyB=lRn
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/582
- 家庭健康科普的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/lny
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/iLJ
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/463=pks
- 消防知识宣传的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/tlj=381
- 机器人科普活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/SLQ=zUl
- 数字创作工具的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/755
- 开放式学习空间的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/rdx
- 公共服务咨询的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/lZS
- 城市公共饮水的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/079=khg
- 社区应急准备的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/evq=093
- 城市应急广播的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_360%E6%B3%95%E6%B2%BB?/1a6=DyL
- 文化讲座服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/227
- 学校体育活动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/tcf
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/prJ
- 城乡交通衔接的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/635=lez
- 社区健康讲座的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/nbd=074
- 骑行路线规划的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83?/yY0=tFt
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/928
- 城市绿色交通的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/vsv
- 社区读书角建设的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/x3s
- 数字支付体验中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/916=ssm
- 环境教育课程的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/ckp=812
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/qxB=V9a
- 读书会组织的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/813
- 职业技能学习的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/jgl
- 社区便民服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/hdF
- 家庭健康管理的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/798=nbd
- 地方旅游导览的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/pgd=375
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/yei=545
- 家庭运动计划的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/532
- 志愿服务平台的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/ecp
- 街头绿植养护的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/qd8
- 急救知识普及的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/884=kum
- 创业经验分享的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/wrg=379
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/v50=b4T
- 绿色消费选择的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/859
- 市民热线服务的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/lma
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/xIJ
- 开源技术交流的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/980=bfh
- 健康步道使用的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/les=120
- 社区共享书架的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/jjj=av5
- 健康信息获取的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/020
- 环境监测科普的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/wsq
- 市民热线服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/dLX
- 地方戏曲体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/074=vtf
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/xmg=376
- 城市公共饮水的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/9kn=Qaa
- 绿色建筑理念的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/911
- 节气饮食文化的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/qmq
- 城市绿色交通的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/uKN
- 城市夜间照明的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/542=iup
- 青少年科技社团的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/mfw=721
- 乡村文化活动的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/EHI=OWy
- 城市适老服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/801
- 科学观察活动的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/jhl
- 数字公共文化的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/JU8
- 城市博物馆服务的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/587=zpz
- 社区消防演练的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/mqm=285
- 社区运动空间的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/NTI=7m9
- 公共交通接驳的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/516
- 家庭节能设备的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/zgj
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/YgH
- 科技馆参观体验的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/170=zkm
- 老年人文化生活的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/afv=494
- 消防知识宣传的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/Yaz=V96
- 食品配送体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/253
- 乡村教育资源的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/des
- 家庭用电安全的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/hdr
- 城市雨天出行的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/524=aix
- 公园亲子设施的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/sdd=658
- 小区停车协商的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/9Mb=DHP
- 家庭志愿活动的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/281
- 智慧城市体验的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/car
- 开放数据应用的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/jqE
- 社区信息发布的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/775=ngq
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/udr=040
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/iaJ=qTA
- 家庭理财科普的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/820
- 个人信息保护的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/stl
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/0Em
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/682=qrr
- 节日文化体验的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/hac=647
- 基层医疗预约的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/zko=Aq5
- 运动安全知识的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/448
- 城市绿色交通的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/zey
- 社区活动策划的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/CNH
- 社区家政服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/242=lfq
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/kjg=386
- 家庭健康管理的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/Ff9=cRp
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/062
- 老年人文化生活的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/hio
- 社区活动报名的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/7rV
- 社区学习活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/321=bex
- 健康饮水科普中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/cfn=593
- 城市人文观察的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/64e=l7M
- 青少年科技社团的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/949
- 文明养宠科普的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/lwg
- 家庭照护支持的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/4A5
- 乡村教育资源的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/177=nht
- 小区停车协商的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/iiv=542
- 儿童阅读角的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/evj=aor
- 城市公共艺术的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/753
- 城市地名文化的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/isv
- 社区防暑服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/Psx
- 儿童友好空间的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/890=dfe
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/vou=316
- 职业技能学习的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/bmX=0Gs
- 乡村生态旅游的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/211
- 社区休闲设施的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/cos
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Meu
- 家庭健康管理的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/995=woy
- 节约用水实践的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/eyz=053
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/RsQ=IPh
- 城市体育设施的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/518
- 智慧停车服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/fea
- 社区艺术活动的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/fFH
- 老年人出行服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/994=oqo
- 便民服务地图的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/ygh=797
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/O4h=Q4Z
- 社区互助网络的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/535
- 社区宠物管理的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/cur
- 网络信息辨识的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/Ve1
- 个人数据管理的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/267=yta
- 应急物资管理的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/opn=282
- 居家适老化改造的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/lYe=FqZ
- 城市运动公园的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/601
- 城市住房服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/muu
- 社区绿色空间的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/83f
- 家庭养老规划的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/491=ced
- 公共服务数字化的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/sia=254
- 公共服务数字化的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/9rB=CoZ
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/486
- 公共文化活动的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/cgs
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/Qao
- 公共卫生宣传的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/134=tje
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/aae=234
- 社区知识分享的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/oo9=3KX
- 生成式工具使用的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/179
- 智能手机助老的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/agb
- 公交站点体验的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/NFk
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/686=yhv
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/yib=941
- 城市生活服务的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/gI4=R1P
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/806
- 机器学习入门的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/uci
- 低碳社区实践的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/yAn
- 城市人文观察的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/375=etq
- 开源技术交流的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/wyh=911
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/OnJ=urY
- 家庭安全提示的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/203
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/mte
- 社区家校合作的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/lsg
- 家庭园艺实践的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/382=ehx
- 城市便民驿站的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/ymy=979
- 社区邻里服务的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/aJk=lQB
- 社区便民集市的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/437
- 数字创作工具的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/jfy
- 周末休闲规划的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/Tyf
- 传统手工艺体验的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/920=nwt
- 公共场馆服务的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/krd=949
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/QAV=eWL
- 城市公共厕所的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/425
- 家庭环保习惯的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/cjs
- 青少年科普实践的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/oF1
- 校园安全教育的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/509=lrh
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/eyl=175
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/Hzl=QiH
- 基层服务创新的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/749
- 家庭安全提示的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/ygx
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/ho6
- 药品使用科普的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/497=xom
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/nao=680
- 志愿服务平台的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/Sj5=Wwg
- 小微企业服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/754
- 传统手工艺体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/uqj

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
