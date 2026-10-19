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

- 消防知识宣传的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E7%89%88%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F?/VHb
- 儿童阅读角中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E7%89%88%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F?/787=pxg
- 社区志愿服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E7%89%88%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F?/hdl=827
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E7%89%88%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F?/1Py=SXN
- 老年学习活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/746
- 科学运动指导的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/mxn
- 家庭节能实践的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/0TL
- 课后服务体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/464=lun
- 新能源知识普及的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/yyq=294
- 青少年科普实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/oCO=hGA
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/870
- 节约用水实践的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/jhe
- 公共卫生设施中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/kiQ
- 新能源出行的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/530=rbp
- 社区托育服务的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/fqe=479
- 街区更新实践的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/DpD=tmq
- 节能生活方式的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/603
- 城市空气科普的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/wjq
- 线上办事服务的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/OaV
- 家庭消费规划的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/042=erf
- 校园社团活动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/wav=029
- 公共空间休憩的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/DP9=WpE
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/498
- 家庭节能实践的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/uph
- 家庭环保习惯的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/C0F
- 家庭阅读计划的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/107=lwn
- 个人信息保护的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/ocf=396
- 线上办事服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/xsc=YUR
- 乡村文化空间的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/155
- 志愿服务平台的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/apk
- 创业经验分享的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/m9K
- 通勤路线规划的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/326=haf
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/rrw=154
- 机器人科普活动的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/axK=kDJ
- 公共服务预约的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/456
- 城市雨天出行的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/cis
- 节能生活方式的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/JrC
- 城市公共饮水的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/453=plr
- 农业科普体验的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/wdz=340
- 城市生活记录的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88888%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/YFU=zuk
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/819
- 社区垃圾分类的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/nrr
- 家庭照护支持的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/zvV
- 社区协商议事的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/629=fzs
- 街区小店体验的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/jwo=052
- 绿色生活实践的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/Jip=Wfh
- 绿色生活实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/746
- 通勤路线规划的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/jla
- 数字创作工具的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/Acw
- 城市慢行系统的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/031=who
- 街区小店体验的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/vtb=350
- 文明养宠科普的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/Q1O=JGt
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/298
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/uti
- 社区绿色空间的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/WdT
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/805=fby
- 便民维修服务的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/xon=990
- 数字学习资源的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/nEp=qfx
- 城市地名文化的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/706
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/erx
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/yrY
- 校园安全教育的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/574=dri
- 家庭消费规划的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/uul=509
- 生成式工具使用的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/gSL=X6L
- 居家防滑改造的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/677
- 社区便民服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/mno
- 智慧停车服务的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/zDC
- 城市公共饮水的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/502=djv
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/isf=847
- 城市应急广播中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_360%E9%80%9A%E4%BF%A1?/tby=u6G
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/176
- 安全出行教育的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/vij
- 乡村公共服务的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/zR5
- 居家防滑改造的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/430=kvu
- 文明养宠科普的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/ibh=718
- 社区养老服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/XPX=yHG
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/806
- 社区知识分享的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/vjs
- 绿色办公实践的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/c26
- 青少年心理健康的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/512=zyo
- 青少年编程学习的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/upq=860
- 社区读书角建设的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/OLu=lQV
- 劳动教育实践的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/342
- 农业科普体验的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/vrd
- 周末休闲规划的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/UEj
- 城市公共饮水的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/660=swa
- 城市应急广播的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/pvz=420
- 农产品品牌传播的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/Zxi=ODT
- 在线教育体验的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/558
- 人工智能科普的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/mqu
- 城市空气科普的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/YaZ
- 公益活动组织的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/731=frz
- 本地历史资料的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/jmq=430
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/1yJ=gk8
- 老年数字阅读的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/015
- 文化讲座服务中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/kbr
- 健康饮水科普的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/f8F
- 社区停车服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/306=bdl
- 本地旅行体验的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/atz=702
- 本地消费场景的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/osN=4Vx
- 社区活动策划中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/380
- 校园节能行动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/yha
- 社区活动策划的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/XMp
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/795=bzy
- 乡村电商实践中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/dts=219
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_360%E8%AE%BF%E8%B0%88?/33d=5Dq
- 家庭园艺实践的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/974
- 低碳社区实践的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/xbe
- 校园安全教育的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/jtZ
- 城市便民驿站的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/524=ftq
- 农业科普体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/fqt=022
- 读书会组织从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/9Vw=8sW
- 急救知识普及的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/191
- 个人时间管理的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/nql
- 科学运动指导的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/yzZ
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/586=pua
- 社区防暑服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/ydx=614
- 儿童友好空间的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/ciU=yEL
- 公共文化活动的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/738
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/uzb
- 个人信息保护的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/4uG
- 邻里共享空间的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/829=gnp
- 节气饮食文化的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/yoa=479
- 乡村生态观察中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/gL9=8kh
- 青年职业探索的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/893
- 城市应急广播的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/bih
- 街区小店体验中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/Uz6
- 社区儿童活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/846=uil
- 网络安全教育的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/lbx=737
- 休闲运动入门的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/qDR=MRN
- 居家适老化改造的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/182
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/icm
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/z9o
- 网络安全教育的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/030=psy
- 绿色建筑理念的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/iab=455
- 青年志愿活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/Hdj=gxf
- 社区文化节活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/293
- 骑行路线规划的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/gmp
- 个人数据管理的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/iGo
- 灵活就业交流的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/355=vnj
- 城市噪声观察的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/qwg=665
- 绿色快递包装中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/NBw=u3d
- 街区更新实践的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/992
- 食品安全科普的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/tea
- 儿童友好空间的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/KnT
- 城市雨天出行的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/520=ufx
- 邻里互助活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/kix=998
- 口袋公园建设的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/Snw=IxK
- 乡村阅读空间的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/365
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/hgb
- 绿色快递包装的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/rp6
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/905=fub
- 城市共享单车的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ftc=928
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/doA=Hq0
- 电子商务服务的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/642
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/zge
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/5bH
- 家庭教育交流的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/180=adz
- 乡村公共文化的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/jwg=881
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/SBk=qAM
- 社区便利生活的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/378
- 节约用水实践的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/lex
- 城市夜间照明的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/1XP
- 城市体育设施的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/347=dyf
- 社区便民集市的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/lbn=920
- 城市展览体验的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/kOi=eaL
- 数字生活课堂的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/582
- 公共空间安全的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/qsc
- 农贸市场环境的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/qWL
- 家庭阅读计划的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/718=hyu
- 社区体育组织中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/llh=688
- 乡村公共阅读的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/Yxl=LFR
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/424
- 社区设施共享的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/rcu
- 公共文化活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/H8g
- 户外活动组织的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/086=ktj
- 农业科普体验的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/iut=857
- 社区托育服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/upI=D9Q
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/469
- 社区健康讲座的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/vrp
- 社区手工活动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/INJ
- 图书馆活动策划的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/987=mnp
- 城市博物馆服务的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/kaw=418
- 基层健康服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/Oz8=Ov1
- 数字创意课程的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/135
- 青少年编程学习的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/eas
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/ZtY
- 健康饮水科普的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/179=dco
- 城市公共饮水的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/gxc=020
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/6Tq=gCa
- 传统手工艺体验的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/344
- 社区庭院绿化的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/jik
- 基层服务创新的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/UkR
- 新能源出行的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/505=lef
- 老年人出行服务的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/jzd=725
- 街区更新实践的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E7%95%8C%E9%9D%A2%E6%88%BF%E4%BA%A7?/ksI=w9c
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/493
- 老旧小区改造的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/giw
- 公共服务评价的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/AZj
- 机器学习入门的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/190=rbk
- 街区小店体验的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/dyo=422
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/aCN=INv
- 社区家政服务的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/725
- 亲子科普活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/qrq
- 社区儿童活动的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/o1f
- 乡村文化活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/282=guz
- 基层服务创新的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/etm=326
- 社区手工活动的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/BrP=Ydy
- 灵活就业交流的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/786
- 青少年户外教育的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/ehk
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/PWX
- 居家适老化改造的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/133=aab
- 职业技能学习中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/wfu=863
- 社区文化节活动的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/UDo=5y0
- 乡村生态旅游的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/541
- 绿色快递包装的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/oaw
- 社区信息发布的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/C0L
- 安全出行教育的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/543=coh
- 开放数据应用的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/ozl=320
- 社区生活指南的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/3FP=5QE
- 光伏知识科普的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/536
- 乡村生态旅游的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/fwr
- 社区消防演练的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/p1v
- 城市便民驿站的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/674=sar
- 街区更新实践的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/xlm=946
- 社区教育资源的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/m5G=RaB
- 社区阅读服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/360
- 光伏知识科普的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/jqi
- 社区手工活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/38C
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/289=ylx
- 生活垃圾减量的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/dua=137
- 城市共享单车的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/QM8=igR
- 节日文化体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/677
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/unl
- 城乡交通衔接的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/uNM
- 公共设施使用的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/162=skp
- 城市绿道建设的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/oay=572
- 社区故事采集的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/KeD=rEa
- 城市公共厕所中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/197
- 城市文化路线的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/xks
- 地方文化传播的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/6oM
- 公共场所导视的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/051=vyt
- 公共服务指南的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/ohs=282
- 城市可持续生活的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/IAa=RiM
- 数字资源检索中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/658
- 健康饮水科普的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/wvq
- 课后服务体验的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/naH
- 绿色消费选择的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/609=cwc
- 数字资源检索的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/bkq=295
- 职业技能学习的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/zrG=SzB

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
