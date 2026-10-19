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

- 城市应急广播的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/210
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/ajh
- 旧物循环利用的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/UZ6
- 社区便利生活的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/123=ytn
- 生活服务数字化的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/tqa=796
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/5Hi=5mh
- 生活垃圾回收的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/390
- 科普展览体验的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/nei
- 家庭消费规划的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/Z1A
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/092=put
- 学校体育活动的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/blr=890
- 便民服务窗口的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/HKa=X8C
- 科普展览体验的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/341
- 安全出行教育的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/wrn
- 志愿服务平台的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/UOp
- 本地消费场景的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/048=brr
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/qjd=757
- 数字学习资源的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/BlJ=Tp0
- 便民服务地图的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/715
- 社区邻里服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/pax
- 无障碍出行的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/1Rz
- 数字生活课堂的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/207=iis
- 骑行路线规划的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/qna=230
- 城市空气科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/jb6=D2h
- 志愿服务平台的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/485
- 数字阅读服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/iaw
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/rX9
- 节能家电使用的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/392=opp
- 老年数字阅读的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/bcz=118
- 居家防滑改造的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/5JY=ljy
- 社区托育服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/334
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/yfc
- 城市住房服务的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/me5
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/358=exk
- 社区快递服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/fim=224
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/Zbq=3ZB
- 老年学习活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/608
- 课后服务体验的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/bve
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/vGL
- 节气饮食文化的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/640=yom
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/zba=722
- 健康饮食教育的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/CR8=5RQ
- 社区宠物管理的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/759
- 社区设施共享的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/jdf
- 城市文化路线的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/w2T
- 城市游园体验的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/755=ffs
- 食品安全科普的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/qkr=989
- 城市地名文化的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/IBn=ApU
- 电子商务服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/446
- 居民健康教育的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/gmj
- 家庭饮食安排的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/ktf
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/509=max
- 家庭用电安全中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/elp=558
- 公共文化活动的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/lj1=rAI
- 生活垃圾减量的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/748
- 急救知识普及的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/kzf
- 家庭阅读计划的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/pf2
- 家庭园艺实践的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/684=oul
- 无障碍出行的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/yjw=621
- 老旧小区改造的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/6n7=7UI
- 老年运动活动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/718
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/quo
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/ugh
- 数字政务体验的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/334=cxt
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/wqi=916
- 城市便民驿站的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/iLI=nOF
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/715
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/nll
- 居民健康教育的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/HPV
- 无障碍出行的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/301=eam
- 城市地名文化的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/eri=903
- 社区便利生活的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/pZ4=zJO
- 社区绿色空间的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/167
- 农产品消费体验的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/heh
- 城市空气科普的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/D09
- 城市共享单车的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/695=iuh
- 终身学习资源的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/lig=399
- 健康步道使用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/Clv=m5u
- 小区停车协商的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/370
- 数字政务体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/eoq
- 环境教育课程的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/Bb2
- 城市建设科普的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/889=smr
- 公共设施维护的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/nmr=603
- 地方文化传播的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_999%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/X3j=nLa
- 新能源知识普及的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/187
- 社区应急准备的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/afy
- 家庭消费规划的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/Qdb
- 社区家政服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/700=owo
- 社区艺术活动的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/uot=285
- 城市游园体验的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/5VC=cj8
- 便民服务窗口的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/604
- 城市住房服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/nip
- 社区故事采集的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/CjQ
- 家庭节能设备的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/934=rcq
- 社区邻里服务的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/qyu=692
- 家庭养老规划的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/3mw=djE
- 社区老年食堂的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/432
- 街头绿植养护的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/ipo
- 社区活动空间的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/fgQ
- 社区活动策划的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/833=brf
- 儿童友好空间的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/atu=610
- 乡村公共服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/rxo=s0z
- 社区活动空间的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/441
- 低碳社区实践的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/wmz
- 绿色办公实践的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/z6o
- 智慧城市体验的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/494=aan
- 绿色办公实践的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/fuz=706
- 校园节能行动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/68A=Ap5
- 环境监测科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/367
- 社区生活指南的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/srn
- 社区公共卫生的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Cmp
- 口袋公园建设的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/327=juf
- 安全出行教育的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wwd=838
- 科普展览体验的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/JB7=CjY
- 社区老年食堂的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/936
- 公共交通接驳的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/fik
- 社区设施共享的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/BPk
- 青少年编程学习中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/191=txh
- 公共交通信息服务的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/bet=249
- 乡村产业科普的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/QUW=WzT
- 公共服务咨询的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/658
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/bht
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/0jF
- 本地消费场景的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/411=qzp
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/tvc=817
- 青少年科普实践的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/5cA=GfO
- 城市展览体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/297
- 在线教育体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/ydl
- 城市绿色交通的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/bhc
- 家庭阅读计划的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/523=kgn
- 个人信息保护的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/neu=070
- 街头绿植养护的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/B16=WU1
- 社会体育指导的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/744
- 骑行路线规划的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/jrv
- 社区防暑服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/ygK
- 文明养宠科普的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/798=voz
- 城市适老服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/zca=939
- 公共服务指南的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/zO1=Z37
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/981
- 乡村教育资源的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/zky
- 就业技能培训的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/YLI
- 在线教育体验的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/190=wko
- 医院导诊服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/lza=062
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/naZ=c5b
- 跨代沟通活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/801
- 公共设施使用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ixe
- 社区便利生活的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cnm
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/650=eak
- 地方文化传播的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bir=935
- 在线学习体验的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/PDl=XPc
- 在线学习体验的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/747
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/jhd
- 老年数字阅读的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/TTA
- 创业经验分享的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/900=yuk
- 家庭饮食安排的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/pfn=134
- 社区公共卫生的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/mcS=mgH
- 便民信息查询中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/651
- 生活技能分享的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/prz
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/ZtF
- 社区家政服务的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/234=zaa
- 校园安全教育的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/oot=209
- 乡村公共服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/5Ch=1Gj
- 环境监测科普的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/292
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/fsu
- 社区宠物管理的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/mm8
- 开放式学习空间的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/859=cdf
- 老年学习活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/wtn=891
- 青少年编程学习的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/1nB=0Y4
- 乡村产业科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/838
- 老年人日常照护的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/sih
- 学校体育活动的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/nss
- 街区更新实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/725=nhr
- 志愿服务平台的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/gjz=281
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/QIO=s2w
- 社区环保活动的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/515
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/jyj
- 城市适老服务的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/Jxv
- 城市微更新实践中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/346=ybc
- 线上办事服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/zxu=275
- 社区艺术活动的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/2Pw=4fJ
- 环境监测科普的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/167
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/mpq
- 社区应急准备的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/a2T
- 家庭消费规划的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/564=ekk
- 街区小店体验的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/voc=336
- 街区绿化养护的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/83n=aug
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/876
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/gvr
- 节能家电使用的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/Aio
- 开放数据应用的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/287=ufe
- 传统节日科普的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/dtk=436
- 市民意见收集的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/op7=D2s
- 文化讲座服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/997
- 乡村公共服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/hfe
- 社区法律科普的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/kOO
- 地方美食文化的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/380=agq
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/inx=618
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/ckP=XFV
- 乡村教育资源的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/480
- 城市雨天出行的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/jqm
- 公共服务评价的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/eGR
- 社区教育资源的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/044=uqf
- 社区学习活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/ike=382
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/kcm=U8n
- 社区文化节活动的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/550
- 地方民俗记录的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/eqr
- 无障碍出行的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/45Z
- 旧物循环利用的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/398=udq
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/zeb=368
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%90%97_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/7pf=u4E
- 家庭运动计划的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/449
- 科学健身方法的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/xxr
- 个人数据管理的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/qda
- 农业科普体验的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/132=xod
- 口袋公园建设的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/gsl=779
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91%2814%E5%9C%BA%29_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/a3w=CBV
- 数字课堂应用的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/300
- 数字生活课堂的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/epq
- 乡村生态观察的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/PDC
- 社区协商议事的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/636=ase
- 社区老年食堂的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/ezl=597
- 便民信息查询的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E5%8D%81%E5%9B%9B%E5%9C%BA_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/Miw=DXn
- 生活垃圾减量的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/572
- 城市步行环境的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/tem
- 日常摄影记录的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/bYk
- 小区电梯维护的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/860=lyb
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/bcz=576
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E9%A6%96%E9%A1%B5%28%E5%AE%98%E7%BD%91%29%E6%BE%B3%E5%AE%A2%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/yiI=jto
- 社区手工活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/143
- 公共交通接驳的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/hly
- 家庭照护支持的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/3fr
- 数字素养提升的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/633=wjj
- 校园节能行动的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/civ=966
- 绿色生活实践的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%AE%A2%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E7%94%A8%E4%BA%86_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/e1M=LiU
- 社区互助网络的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/207
- 城市夜间照明的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/ixi
- 社区信息发布中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/FGe
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/548=odn
- 旧物循环利用的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/zwe=999
- 新能源出行的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%BD%91%E8%B6%B3%E5%BD%A9%E5%BF%85%E5%8F%91%E7%9B%88%E4%BA%8F%28%E6%8C%87%E6%95%B0%29_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/WdY=Mcs
- 智慧停车服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/313
- 家庭阅读计划的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/iuc
- 城市社区治理的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/R7B
- 老年数字阅读的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/129=ser
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/zcv=080
- 儿童运动体验的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29%E8%B6%B3%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/mo7=Pfl
- 科学教育活动的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/202
- 地方民俗记录的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/fyj
- 老年学习活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/XvQ
- 城市适老服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%AE%A2%E7%BD%91%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/201=cql

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
