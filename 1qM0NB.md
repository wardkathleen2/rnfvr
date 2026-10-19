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

- 社区知识分享的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/mch=963
- 在线学习体验的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/5BB=Xw7
- 城市生活记录的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/903
- 社区便民集市的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/xqb
- 社区家校合作的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/sBH
- 老年人文化生活的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/321=gnc
- 人工智能科普的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/stp=526
- 社区法律科普的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/XEJ=tEk
- 课后服务体验的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/946
- 老年人出行服务的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/ybr
- 小区公共照明的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/7Op
- 乡村公共服务的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/433=zpt
- 社区便民集市的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/yty=339
- 社区互助网络的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ev88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/T1h=zq0
- 文明养宠科普的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/162
- 老年运动活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/ura
- 乡村文化空间的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/7zq
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/693=mka
- 社区老年食堂中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/qmx=162
- 科学运动指导的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/dtS=0NY
- 校园节能行动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/985
- 科学信息获取的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/hwq
- 小区电梯维护的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/PGX
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/808=lvp
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/kvo=666
- 机器人科普活动的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev88-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/q9K=7yW
- 食品配送体验的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/686
- 个人时间管理中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/nej
- 人工智能科普的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/Yg2
- 网络安全教育的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/187=hyl
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/vim=968
- 公共空间休憩的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Ev88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/bWR=vxJ
- 城市公共标识的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/738
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/ado
- 基层医疗预约的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/WSl
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/036=muv
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/sje=890
- 家庭志愿活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/Zu0=N8E
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/831
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/amk
- 骑行路线规划的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/EQO
- 学校食育活动的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/356=dxu
- 社区读书角建设中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/nkp=933
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/D47=aYl
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/214
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/jep
- 社区快递服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/Kpe
- 开源技术交流的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/265=joz
- 社区公共卫生的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/ako=878
- 乡村文化活动的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Ev88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/GZT=k2y
- 健康信息获取的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/491
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/aqh
- 城市公共座椅的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/fU1
- 城市公共自行车的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/328=ihb
- 社区生活指南的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/onr=129
- 青少年科普实践的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/DLw=MBT
- 家庭运动计划的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/043
- 社区读书角建设的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/vuf
- 绿色校园实践的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/mMx
- 居家防滑改造的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/215=jff
- 城市展览体验的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/pov=200
- 数字阅读服务的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Ev88-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/l3a=JBu
- 数字地图应用的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/636
- 小区停车协商的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/gta
- 运动安全知识的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/eUU
- 家庭网络使用的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/158=hbz
- 社区运动空间的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/rsc=021
- 家庭环保行动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev88-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/Auk=6vD
- 社区商业活力中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/138
- 人工智能科普的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/gat
- 公共健身器材的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/JvN
- 城市文明实践的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/992=jgg
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/ktp=298
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/duP=u1A
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/694
- 节气饮食文化的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/gbs
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/Rzt
- 公共卫生宣传的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/468=akm
- 老年人日常照护的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/nhy=840
- 社区宠物管理的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/k8X=WqO
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/509
- 家庭收纳实践的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/aiu
- 青年就业服务的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/3K9
- 在线学习体验的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/647=gam
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/jae=302
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F?/1p5=Xmk
- 绿色快递包装的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/480
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mcx
- 家庭环保行动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/3ZI
- 街区小店体验的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/235=gqw
- 智能手机助老的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qke=196
- 通勤路线规划的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/UEV=M1G
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/388
- 公交无障碍服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/edk
- 光伏知识科普的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/w4z
- 课后服务体验的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/893=onb
- 青少年科普实践的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/nnj=098
- 电动汽车充电的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/cHK=lNJ
- 课后服务体验的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/515
- 社区教育资源的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/fqa
- 科学信息获取的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/yb5
- 数字地图应用的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/374=mda
- 生活服务数字化的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/awy=408
- 乡村电商实践的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/xc6=82P
- 城市便民驿站的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/976
- 社区教育资源的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/qnm
- 家庭消费规划的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/B5K
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/876=kod
- 家庭照护支持的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/rht=298
- 机器学习入门的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/cBf=sM4
- 劳动教育实践的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/825
- 家庭运动计划的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/era
- 就业技能培训的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/yRM
- 城市生活服务的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/766=nkw
- 校园安全教育的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/rwi=753
- 邻里共享空间的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/K2a=3dd
- 城乡交通衔接的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/115
- 城市地名文化的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/nby
- 城乡公共服务的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/lhy
- 儿童友好空间的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/857=czd
- 社区垃圾分类的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/jst=253
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%9D%E9%99%A9?/kls=6xm
- 节气饮食文化的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/142
- 社区绿色空间的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/rfc
- 便民服务窗口中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/HUw
- 青少年科普实践中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/583=qdj
- 科普展览体验的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/qvq=530
- 城市文化路线的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/YxZ=rIp
- 便民服务地图的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/204
- 家庭理财科普的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/pzz
- 公共服务预约的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/iHE
- 物业服务沟通的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/173=hrp
- 数字生活课堂的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/pez=078
- 小区电梯维护的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/VxN=aUl
- 小区停车协商的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/114
- 社区托育服务的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/dbo
- 智慧城市体验的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/Hgl
- 社区便民集市的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/397=sxf
- 社区家政服务的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/uqu=786
- 绿色出行服务的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/16Z=69a
- 公共文化活动的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/084
- 老旧小区改造的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/nfn
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/fvi
- 网络信息辨识的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/134=obj
- 老年数字阅读的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/neq=885
- 地方民俗记录的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%BB%E4%B9%A6?/0Sy=7qm
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/739
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/qnj
- 公益活动组织的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/COS
- 城市生活记录的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/869=awk
- 社区活动空间中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/utm=396
- 生成式工具使用中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/gad=je2
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/469
- 家庭环保行动的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/wii
- 开源技术交流的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/8XR
- 劳动教育实践的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/827=phr
- 环境教育课程的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/vof=502
- 公共空间安全的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/dmg=ngo
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/458
- 生活垃圾回收的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/cyu
- 公共交通接驳的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/OYk
- 便民维修服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/481=fyu
- 便民信息查询的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/kzb=846
- 文化场馆预约的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/8Jz=TPO
- 节能家电使用的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/297
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/xwe
- 社区设施共享的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/7A9
- 社区环保活动的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/531=vvf
- 科学健身方法的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/ujn=665
- 周末休闲规划的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/oD5=HhO
- 电子商务服务的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/218
- 城市住房服务的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/gky
- 家庭教育交流的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/MTC
- 老旧小区改造的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/507=hjp
- 城市公共艺术的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/unf=836
- 公共空间休憩的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%99%BE%E7%A7%91?/RLk=s9S
- 社区故事采集的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/411
- 终身学习资源的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/aku
- 城市慢行系统的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/cul
- 绿色出行服务的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/184=qah
- 社区商业活力的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/wuc=018
- 科学信息获取的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/xiN=30Z
- 社区菜市场服务的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/960
- 老年人日常照护的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/tgp
- 科普展览体验的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/TKg
- 市民意见收集的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/907=zoe
- 基层服务创新的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/zgn=559
- 社区阅读服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/pVO=WTh
- 社区协商议事的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/376
- 数字地图应用的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/kng
- 文化讲座服务的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/MIV
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/119=rmz
- 城市地名文化的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/dvd=215
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360?/nbB=uNj
- 城市公共空间的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/581
- 全民阅读推广的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/arw
- 社区托育服务的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/Vjs
- 数字素养提升的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/327=fuh
- 城乡公共服务的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/nux=297
- 科学信息获取的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/i3i=3sN
- 乡村文化活动的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/432
- 老年智能设备的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/imu
- 科技馆参观体验的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/1RB
- 城市慢行系统中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/280=afo
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/vkk=280
- 邻里互助活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/Y93=hsz
- 基层医疗预约的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/598
- 地方文化传播的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/bqp
- 安全出行教育中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/0XW
- 老旧小区改造的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/048=ymh
- 城市公共标识的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/vyx=120
- 公共卫生设施的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/YwZ=B7h
- 城市社区治理的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/247
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/qea
- 社区交通安全的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/VL7
- 农业科普体验的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/796=vab
- 乡村公共阅读的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/ozw=865
- 社区运动空间的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/VN3=BCs
- 城市展览体验的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/254
- 创业经验分享的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/cop
- 校园社团活动的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/LQd
- 公共空间导览的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/127=tmt
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/gyg=565
- 公共服务咨询的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/zus=JPS
- 数字素养提升中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/986
- 社区便民服务中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/pns
- 居家防滑改造的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/76d
- 开源技术交流的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/883=fsg
- 乡村阅读活动的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/hwr=642
- 数字支付体验的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/vWw=eaK
- 社区故事采集的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/987
- 传统节日科普的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/ngr
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/jiE
- 骑行路线规划的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/575=xmy
- 社区活动空间的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/zli=835
- 社区便民集市的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/Pk8=Ila
- 城市博物馆服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/557
- 社区花园共建的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/xyl
- 青少年科普实践的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/g5J
- 社区便利生活的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/660=crx
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/tep=227
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/7td=X9f
- 医院导诊服务的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/583
- 急救知识普及的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/gub
- 家庭收纳实践的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/I1g
- 家庭节能实践的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/206=mum
- 健康饮食教育的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/lzn=876
- 社区心理支持的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/7o5=rE7
- 便民服务窗口的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/381
- 儿童安全出行的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/lyi

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
