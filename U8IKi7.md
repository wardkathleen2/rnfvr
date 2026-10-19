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

- 老年运动活动的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/xga=698
- 开放数据应用的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/9O7=DF8
- 社区心理支持的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/625
- 城市基础设施的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/pqg
- 家庭消费规划的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/D9W
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/805=aqn
- 社区活动报名的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/yvk=849
- 在线学习体验的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/QE7=jQM
- 社区知识分享的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/932
- 社会体育指导的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/roa
- 社区便利生活的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/YsJ
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/135=bec
- 日常摄影记录的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/aww=456
- 老年人日常照护的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/gqH=ZEw
- 社区设施共享的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/876
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/cxy
- 社区阅读服务的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/9NJ
- 城市步行环境的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/377=clk
- 农贸市场环境的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/pax=213
- 本地旅行体验的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/mSU=KnR
- 文明养宠科普的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/500
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/app
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/p3t
- 社区活动策划的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/134=qaq
- 读书会组织的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/cyx=789
- 运动安全知识的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%8F%91_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/QJ3=tvi
- 城市适老服务的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/688
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/ycr
- 药品使用科普的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/iGW
- 消防知识宣传的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/562=njw
- 城市展览体验的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/saz=251
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%80%81%E7%89%88%E6%9C%AC%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/49R=f3R
- 数字艺术创作的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/631
- 城市夜间照明的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/zvg
- 数字便民地图的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/21H
- 户外活动组织的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/619=eat
- 无障碍信息设计的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/yez=935
- 开放数据应用的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/JmD=h0x
- 儿童友好空间的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/187
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/lkg
- 市民热线服务的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/yeJ
- 社区读书角建设的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/046=rxa
- 读书会组织的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/mmd=638
- 城市公共饮水的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/Igf=8Fc
- 社区知识分享的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/494
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/xll
- 应急物资管理的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/GFN
- 本地历史资料的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/728=nvm
- 城市雨天出行的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/agd=415
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/Y31=EL7
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/160
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/yzb
- 城市步行环境的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/FSx
- 医院导诊服务的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/593=beg
- 社区知识分享的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/phz=937
- 邻里互助活动的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/eRq=kWU
- 社区设施共享的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/191
- 家庭饮食安排的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/vai
- 文化讲座服务的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/ZsX
- 光伏知识科普的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/073=hie
- 公共交通接驳的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/qqn=497
- 老年人出行服务的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/794=sjb
- 城市绿色交通的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/410
- 跨代沟通活动的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/ndw
- 家庭科学教育的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/zSj
- 城市绿道建设的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/748=dxh
- 社区菜市场服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/ssj=049
- 公共场所导视的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/7ub=3G3
- 便民信息查询的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/485
- 科学教育活动的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/aeb
- 公共服务咨询的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/G53
- 儿童户外活动的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/337=znx
- 老年智能设备的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/ndq=814
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/oa4=SiL
- 绿色出行服务的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/802
- 社区生活指南的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/tlh
- 城市公共艺术的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/88Z
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/051=arp
- 传统节日科普的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/lbi=976
- 社区学习活动的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/CJb=6uO
- 社区便民集市的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/684
- 社区商业活力的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/lsu
- 文明养宠科普的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/cp9
- 儿童户外活动的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/109=vsa
- 社区志愿服务的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/fnf=035
- 通勤路线规划的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/6Z9=gxi
- 数字素养提升的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/281
- 社区阅读服务中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/ajf
- 本地历史资料的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/C8S
- 青年志愿活动中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/662=dii
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/jgj=716
- 社区协商议事的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/5lv=bvo
- 公共服务评价的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/979
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/ibb
- 家庭节能设备的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/wKL
- 日常摄影记录的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/336=cix
- 青少年户外教育的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/tim=905
- 公共服务指南的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/iej=xh8
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/147
- 家庭节能实践的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/jyk
- 数字资源检索的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/J9A
- 创业经验分享的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/606=rvl
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/vpx=743
- 数字创意课程的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/3Ts=Pvj
- 社区艺术活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/221
- 社区读书角建设的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/fyw
- 青少年编程学习的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/s5c
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/862=bzf
- 节假日出行安排的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/gbc=771
- 城市展览体验的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/cHj=efj
- 家庭收纳实践的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/962
- 休闲运动入门的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/vqn
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/Wx5
- 城市体育设施中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/237=tqs
- 社区家校合作的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/ssj=619
- 城市住房服务的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/ZPz=knT
- 公共场所导视的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/560
- 家庭网络使用的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/srz
- 城市步行友好的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/E5H
- 校园社团活动的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/837=apg
- 社区消防演练的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/qbw=452
- 旧物循环利用的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/BzL=tM3
- 城乡交流活动的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/452
- 终身学习资源的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/tum
- 街区道路维护的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/4Hz
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/006=mfa
- 社区交通安全的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/jfh=087
- 公共空间照明的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/3cX=o97
- 家庭园艺实践的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/011
- 农业科普体验的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/uam
- 城市人文观察的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/lcS
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/429=mcm
- 数字档案服务的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/rue=273
- 邻里互助活动的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/cFr=1qC
- 创业经验分享的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/419
- 社区儿童活动的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/ftx
- 智能手机助老的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/ims
- 绿色出行服务的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/775=yfl
- 家庭饮食安排的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/opd=806
- 无障碍出行的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/Ge5=HN7
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/063
- 健康信息获取的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/gqf
- 家庭网络使用的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/No4
- 食品配送体验的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/245=nwl
- 数字生活课堂的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/fbr=721
- 开放式学习空间的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_360%E6%8A%95%E7%A5%A8?/Utz=UBs
- 本地历史资料的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/867
- 街区小店体验的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/xei
- 城市公共厕所的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/FOp
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/807=dfa
- 健康饮水科普的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/pfk=760
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/4Ur=Gti
- 本地消费场景的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/666
- 街区绿化养护的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/hhg
- 生活服务数字化的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/NLd
- 家庭养老规划的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/098=dgc
- 社区活动报名的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/xso=532
- 街区小店体验的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/lwH=Vxi
- 健康饮水科普的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/090
- 智能手机助老的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/ikf
- 家庭园艺实践的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/HYX
- 远程协作工具的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/183=ipj
- 公共场所导视的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/yzt=525
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/RnN=zDZ
- 城市农夫市集的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/222
- 老年人日常照护的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/jty
- 城市体育设施的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/iox
- 社区文化节活动的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/217=tew
- 地方旅游导览的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/qvr=088
- 社区养老服务的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/2oA=J63
- 家庭饮食安排的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/625
- 家庭急救准备的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/taa
- 数字阅读服务的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/Lzd
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/703=owr
- 社区故事采集的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/fdv=172
- 租房信息服务的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/gOD=QP4
- 社区垃圾分类的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/911
- 城市微更新实践的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/iss
- 公共空间休憩的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/z6k
- 绿色生活实践的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/473=vvp
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/arg=134
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/St1=s60
- 城市博物馆服务的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/903
- 市民意见收集的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/ork
- 社区知识分享的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/v6v
- 邻里共享空间的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/191=lio
- 传统节日科普的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/vlj=009
- 软件开发学习的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/kaN=H32
- 骑行路线规划的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/815
- 家庭健康管理的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/vpm
- 口袋公园建设的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/W70
- 居家适老化改造的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/200=oqp
- 低碳社区实践的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/qcf=169
- 老年人日常照护的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/HyH=Knv
- 城市骑行环境的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/080
- 社区共享书架的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/tqz
- 地方旅游导览的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/97Y
- 社区商业活力的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/581=dnz
- 社区互助网络的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/qun=398
- 绿色出行服务的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/vIO=YWk
- 社区阅读服务的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/150
- 生活垃圾减量的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/eys
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/iMA
- 节约用水实践的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/926=fci
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/vay=409
- 社区知识分享的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_360%E5%81%A5%E8%BA%AB?/DMv=gBd
- 社区邻里服务的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/449
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/nts
- 信息无障碍体验的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/h5A
- 数据分析入门的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/029=imo
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/hxt=833
- 绿色消费选择的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/XX1=6Tq
- 城市应急科普的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/203
- 社区应急准备的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/bny
- 社区防暑服务的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/uyn
- 城市公共厕所的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/621=plu
- 城市博物馆服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/jau=912
- 读书会组织的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_36%E6%B0%AA%E5%AE%89%E9%98%B2?/RMY=zy4
- 日常摄影记录的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/691
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/cod
- 新能源知识普及的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/tQX
- 社区便民服务的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/743=tzk
- 数字学习资源的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/rqb=973
- 居民健康教育的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/mv6=XvL
- 城市博物馆服务的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/874
- 绿色校园实践的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/atm
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/wIa
- 租房信息服务的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/850=vom
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/twg=035
- 城市农夫市集的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/2vs=i9t
- 老年人文化生活的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/267
- 节能家电使用的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/wdv
- 社区手工活动的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/5xv
- 城市适老服务的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/482=wiq
- 社区心理支持的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/uhr=230
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/YTR=yw8
- 城市应急科普的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/170
- 居家适老化改造的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/tan
- 科学运动指导的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/gpo
- 家庭节能实践的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/007=bgm
- 乡村公共文化的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/rtw=328
- 个人时间管理中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_360%E8%BD%AC%E8%BD%BD?/rto=6y0
- 文明养宠科普的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/349
- 城市可持续生活的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/dme
- 低碳社区实践的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/UF3
- 基层医疗预约的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/208=sxn
- 绿色校园实践的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/yzm=336
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/1k2=PCY
- 环境监测科普的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/430
- 网络安全教育中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/hpt

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
