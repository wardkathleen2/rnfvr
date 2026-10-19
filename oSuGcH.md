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

- 社区艺术活动的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/fbR
- 绿色消费选择的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/504=gpv
- 社区养老服务的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/bdq=849
- 公共服务咨询的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/a3j=vVY
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/807
- 线上办事服务的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/tte
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/knV
- 市民意见收集的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/594=sge
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/feu=741
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/beS=3bz
- 生活技能分享的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/535
- 社区防暑服务的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/dyq
- 社区托育服务的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/8XG
- 新能源出行的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/811=drd
- 终身学习资源的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/dca=744
- 社区公共议事的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/Xo3=7hH
- 社区知识分享的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/081
- 城市文化路线的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/oys
- 低碳社区实践的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/tGp
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/017=zyt
- 公共空间休憩的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/hwr=898
- 城市休闲步道的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/juA=VP4
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/990
- 老年人文化生活的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/rny
- 图书借阅体验的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/kbs
- 读书会组织的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/510=pee
- 社区便利生活的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/yim=969
- 邻里互助活动的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/mKO=BMx
- 城市适老服务的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/111
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/muv
- 基层服务创新的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/SKj
- 公共空间导览的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/637=eno
- 数字政务体验的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/dtt=673
- 低碳社区实践的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/42M=oJM
- 智能手机助老的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/382
- 街头绿植养护的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/pzp
- 城市绿道建设的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/b0J
- 科学健身方法的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/490=zrg
- 劳动教育实践的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/cng=198
- 老年数字阅读的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/NNl=x8y
- 软件开发学习的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/657
- 健康饮食教育的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/stw
- 社区庭院绿化的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/bCT
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/018=arp
- 公园亲子设施的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/rgi=386
- 家庭收纳实践的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/KJF=ZhE
- 邻里互助活动的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/632
- 市民意见收集的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/qyk
- 社区家校合作的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/WZf
- 智能家居应用的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/122=fyt
- 生成式工具使用的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/kce=065
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/px4=ipa
- 老年运动活动的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/075
- 城市公共艺术的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/ozz
- 小区公共照明的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/Y3m
- 社区学习活动的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/819=qgg
- 日常摄影记录的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/jpa=342
- 儿童阅读角的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/gu6=Dco
- 环境监测科普的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/320
- 社区托育服务的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/qio
- 城市基础设施的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/EFQ
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/819=mvg
- 青少年心理健康的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/boz=953
- 地方美食文化的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/pFQ=VUx
- 社区运动空间的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/169
- 社区活动空间的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/jeq
- 公共服务评价的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/pPX
- 家庭饮食安排的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/088=heo
- 农贸市场环境的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/sfl=781
- 科学观察活动的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/pXC=je9
- 数字课堂应用的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/394
- 社区绿色空间的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/ulc
- 垃圾分类指导的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/p1z
- 街区小店体验中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/005=sqn
- 城市适老服务的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/hsv=146
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/CsY=p11
- 物业服务沟通的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/784
- 本地旅行体验的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/ijv
- 消防知识宣传的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/jSI
- 小区停车协商的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/199=mkg
- 社区环保活动的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/buf=498
- 乡村生活观察的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/fS1=J6F
- 基层健康档案的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/107
- 家庭环保行动的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/uxk
- 线上阅读资源的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/Gg9
- 老年友好服务的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/195=dnh
- 开源技术交流的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/eos=724
- 本地历史资料的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%8F%B8%E6%B3%95?/S4g=ExJ
- 乡村公共服务的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/560
- 公共服务沟通的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/jsa
- 节假日出行安排中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/2PK
- 城市应急广播的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/018=ecg
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/zfn=033
- 智能家居应用的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/k0T=NQa
- 城市夜间照明的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/857
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/pnv
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/7HX
- 校园节能行动的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/223=cca
- 公益活动组织的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/nah=990
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/Bvi=7hO
- 公共卫生宣传的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/125
- 社区法律科普的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/nms
- 城市公共厕所的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/5bg
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/775=aha
- 就业技能培训的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/nbv=875
- 城市适老服务的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/32r=g8E
- 老年友好服务的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/355
- 社区活动报名的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/uvt
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/IgX
- 家庭运动计划的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/021=xht
- 街头绿植养护的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/quy=795
- 基层健康档案的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/jGx=4zG
- 全民阅读推广的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/782
- 本地历史资料的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/mei
- 城市运动公园的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/R05
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/057=qfd
- 灵活就业交流中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/lzw=116
- 租房信息服务的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/DBU=pB0
- 科学运动指导的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/092
- 公共空间照明的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/efk
- 公共服务沟通的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/Qri
- 生活服务数字化的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/623=zbm
- 城市文明出行的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/nih=193
- 青年志愿活动的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/mXr=QHQ
- 城市噪声观察的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/764
- 老年人日常照护的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/lae
- 地方戏曲体验的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/vjx
- 健康信息获取的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/587=lue
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/wxl=699
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/kTs=crx
- 城市便民驿站中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/660
- 通勤路线规划的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/bdi
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/MPd
- 乡村文化活动的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/675=kec
- 小微企业服务的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/gsj=697
- 数字便民地图的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/6ur=9m9
- 社区活动策划的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/976
- 软件开发学习的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/xgs
- 家庭食品保存的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/Vgr
- 亲子科普活动的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/577=bez
- 旧物循环利用中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/uod=463
- 老年人文化生活的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/BtV=xcr
- 城市适老服务的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/641
- 城市噪声观察的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/zum
- 城市公共标识的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/cud
- 社区手工活动的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/602=yul
- 社区公共卫生的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/xtb=156
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/T1T=Xm9
- 家庭急救准备的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/202
- 社区环保活动的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/zir
- 文化讲座服务的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/Jt9
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/232=iwz
- 绿色消费选择的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/yes=250
- 新能源出行的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/Rhe=5PM
- 生活垃圾回收的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/818
- 城市绿色交通的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/zih
- 青年志愿活动的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/tjl
- 城市应急广播的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/545=rqi
- 数字公共文化的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/aob=603
- 校园节能行动的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/9mg=wQz
- 社区商业活力的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/492
- 城市绿道建设的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/drj
- 数字设备回收的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/oqA
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/178=lhp
- 科学运动指导的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/vgg=376
- 全民健身活动的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/byw=Myl
- 读书会组织的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/466
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/fae
- 社区文化节活动的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/17j
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/705=svx
- 地方美食文化的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/gfk=959
- 城市公共饮水的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/vlF=Zzg
- 本地历史资料的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/542
- 绿色办公实践的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/oiq
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/uJ9
- 物业服务沟通中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/426=jqt
- 城市共享单车的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/zab=314
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/rAE=HAD
- 老旧小区改造的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/682
- 公共服务评价的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/ooh
- 城乡交通衔接的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/XYX
- 城市应急广播的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/675=prm
- 日常摄影记录的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/blw=719
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/SiS=0FR
- 社区快递服务的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/774
- 低碳社区实践的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/hde
- 家庭网络使用的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/RkD
- 青少年编程学习的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/302=yzs
- 乡村电商实践的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/sxw=932
- 开放数据应用的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/oqW=bha
- 智慧城市体验的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/746
- 城市文化路线的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/jbp
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ai1
- 志愿服务平台的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/170=sbh
- 创业经验分享的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pca=591
- 城市树木认养的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/PUM=tmf
- 校园阅读活动的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/617
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/iak
- 社区便民集市的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/Hkz
- 绿色消费选择的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/140=jfe
- 街区更新实践的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/idu=703
- 城乡公共服务的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/w4E=vNr
- 家庭志愿活动的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/038
- 老旧小区改造的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/pff
- 公共卫生设施的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/xIq
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/697=zhz
- 家庭志愿活动的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/zkt=182
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/SpQ=HHD
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/380
- 文明养宠科普的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/qmc
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/VCt
- 乡村教育资源的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/860=vdh
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/tzh=192
- 家庭食品保存的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/cyt=FJn
- 公共设施维护的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/120
- 城市夜间照明的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/ina
- 科普展览体验的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/t7f
- 数字支付体验的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/975=enk
- 智能手机助老的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/ovg=416
- 软件开发学习的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%89%8B%E8%AE%B0?/wc5=vGe
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/247
- 乡村公共文化的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/dzw
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/zqw
- 城市公共标识的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/822=mhk
- 灵活就业交流的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/rim=397
- 城市博物馆服务的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/qfa=squ
- 城乡交通衔接的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/571
- 本地历史资料的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/nwx
- 旧物循环利用的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/x3s
- 日常摄影记录的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/872=kdr
- 个人信息保护的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/iuc=369
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E6%95%B0%E7%A0%81?/4cx=Sze
- 无障碍信息设计的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/124
- 医院导诊服务的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/eqw
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/Qgw
- 老年人日常照护的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/344=bng
- 城市休闲步道的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/oel=024
- 公共卫生宣传的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/1su=B6c
- 文化场馆预约的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/613
- 家庭科学教育的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/fmd
- 科技馆参观体验的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/62k
- 街区更新实践中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/712=fll
- 老年智能设备的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/cdk=025
- 街区小店体验的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/L4r=UBV
- 学校体育活动的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/234
- 社区便民服务的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/dqs
- 家庭安全提示中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/YZ4
- 社区共享书架的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/319=vyy
- 药品使用科普的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/gwp=964
- 社区便利生活的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA?/PSK=VZx

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
