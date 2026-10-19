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

- 急救知识普及的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/cTd
- 家庭节能设备的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/361=tfm
- 旧物循环利用的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/ffh=455
- 公益活动组织的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/BRj=AQD
- 城市文化路线的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/103
- 城市运动公园的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/btw
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/SxT
- 便民信息查询的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/567=tve
- 灵活就业交流的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/bez=457
- 乡村文化空间的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/Ymm=Td0
- 社区活动空间的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/608
- 公共服务数字化的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/nxr
- 科学教育活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/tXl
- 社区运动空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/067=yto
- 城市公共饮水的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/gev=567
- 城市公共厕所的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/NML=jHf
- 城市步行环境的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/699
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/pwr
- 儿童安全出行中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/Kfe
- 远程协作工具的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/835=giz
- 社区活动策划中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/jgn=109
- 社区知识分享的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/U1D=BbS
- 居民健康教育的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/818
- 乡村文化空间的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/dsv
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/yab
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/751=qzu
- 社区商业活力的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/uxe=883
- 日常摄影记录的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/SxU=T5M
- 文明养宠科普的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/640
- 地方民俗记录的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/vke
- 社区活动空间的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/9tt
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/921=hli
- 户外活动组织的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/tcg=793
- 社区阅读服务的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/xGh=Ks2
- 数字资源检索的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/822
- 城市便民驿站的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/tna
- 社区设施共享的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/Bco
- 社区商业活力的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/563=ecl
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/hup=536
- 社区环保活动的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/OXJ=4xy
- 居家防滑改造中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/451
- 社区休闲设施中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/llk
- 气象科普传播的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/9UZ
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/472=dfk
- 数字生活课堂的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/vrf=619
- 社区交通安全的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/5Pd=umD
- 科学信息获取的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/487
- 在线学习体验中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/hkp
- 公共服务沟通的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/92P
- 社区快递服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/828=emg
- 绿色消费选择的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/dck=521
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/NZF=oGg
- 城市绿色交通的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/975
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/uqg
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/qO6
- 乡村文化空间的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/284=vtl
- 城市噪声观察的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/uee=894
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/BJX=WWr
- 城市噪声观察的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/586
- 青少年编程学习的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/kus
- 口袋公园建设的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/gcH
- 公共场馆服务的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/521=mdz
- 家庭志愿活动的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/wle=337
- 青少年户外教育的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/TFz=F4G
- 机器学习入门的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/491
- 老年人文化生活中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/ciu
- 老年智能设备的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/oEy
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/983=zoq
- 传统手工艺体验的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/cos=847
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/V43=2tV
- 老年学习活动的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/308
- 租房信息服务的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/wzv
- 家庭网络使用的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/KyZ
- 健康步道使用的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/769=ybx
- 邻里互助活动的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/ntr=440
- 乡村教育资源的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/TIx=CM4
- 生活垃圾回收的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/184
- 文明养宠科普中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/dib
- 网络安全教育的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/gUh
- 小区公共照明的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/671=dtf
- 校园阅读活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/wll=730
- 社区养老服务的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/yLX=ppr
- 社区应急准备的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/211
- 软件开发学习的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/vvk
- 城市绿道建设的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/mC2
- 灵活就业交流的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/722=kvw
- 城市应急广播的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/fbg=958
- 社区志愿服务的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/oge=xou
- 本地旅行体验的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/947
- 户外活动组织的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/esq
- 老年数字阅读的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mgq
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/003=cmd
- 城市公共厕所的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/yvl=510
- 绿色快递包装的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jDt=Kqp
- 绿色建筑理念的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/864
- 科普展览体验的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/bnu
- 城市树木认养的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/Vxg
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/921=yij
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/kee=504
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/VUY=gjM
- 城市社区治理的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/419
- 校园社团活动的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/qaw
- 社区消防演练的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/rQm
- 城市便民驿站中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/605=pdz
- 乡村文化活动的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/ggn=960
- 城市绿色交通的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/8Qi=CBA
- 低碳社区实践的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/509
- 学校食育活动的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/nfo
- 节气饮食文化的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/CkW
- 乡村生态观察的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/673=pqs
- 城乡交流活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/pto=052
- 社区艺术活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/7o5=uHG
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/769
- 家庭养老规划的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/gqs
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/qzP
- 城市夜间照明的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/042=ars
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/lad=633
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/7YF=KwD
- 城市绿道建设的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/443
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/ajk
- 光伏知识科普的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/KHs
- 环境监测科普的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/141=srh
- 青少年科普实践的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/icj=914
- 城市公共空间的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_36%E6%B0%AA%E9%94%90%E8%AF%84?/r1z=K3F
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/569
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/ytm
- 城市展览体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/Afd
- 城市运动公园的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/199=qhm
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/xow=311
- 食品配送体验的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/dcZ=PKD
- 家庭急救准备的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/719
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/djr
- 乡村产业科普的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/Vxa
- 社区宠物管理的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/844=qcm
- 开源技术交流的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/swv=499
- 绿色生活实践的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/p9n=kgt
- 数字创意课程的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/420
- 学校食育活动的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/nss
- 数字支付体验的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/eQu
- 农业科普体验的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/307=nsv
- 社区绿色空间的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/zvb=155
- 公共空间导览的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/Bk4=1nW
- 乡村文化空间的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/146
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/ftn
- 绿色办公实践的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/pFA
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/753=fxp
- 城市噪声观察的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/cyf=925
- 生活服务数字化中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/AUC=M4k
- 亲子科普活动的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/992
- 城市文明实践的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/rag
- 城市噪声观察的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/z5g
- 节假日出行安排的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/488=yru
- 科技馆参观体验的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/flt=123
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/5Qs=wZL
- 社区艺术活动的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/587
- 居民健康教育中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/knt
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/lX0
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/316=ugz
- 青年职业探索的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/uow=507
- 城市步行友好的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9?/bXP=aNh
- 户外活动组织的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/095
- 休闲运动入门的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/mkj
- 文化讲座服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/Ilh
- 旧物循环利用的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/766=omi
- 城市绿色交通的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/yuf=016
- 基层医疗预约的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/ztb=IYb
- 乡村公共阅读的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/708
- 乡村教育资源的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/bmc
- 社区修缮行动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/j9q
- 线上办事服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/483=ptn
- 乡村公共服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/aon=218
- 社区活动策划的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/2cv=H0j
- 城乡公共服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/945
- 机器人科普活动的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/nih
- 绿色消费选择的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/UUc
- 公共服务评价的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/226=lqw
- 旧物循环利用的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/bak=703
- 智慧停车服务的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/7ac=MGQ
- 公共交通接驳的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/074
- 数据分析入门的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/cjx
- 跨代沟通活动的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/AH6
- 社区商业活力的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/155=zut
- 健康饮食教育中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/esc=466
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/79c=U44
- 街区小店体验的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/221
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/wxk
- 生活垃圾回收的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/dBR
- 青年志愿活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/649=ked
- 城市体育设施的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/czp=157
- 电动汽车充电的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%B6%E8%97%8F?/xkv=vJ6
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/283
- 家庭食品保存的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/mkr
- 数字政务体验的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/e2R
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/667=vur
- 城市夜间照明的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/fax=191
- 节能家电使用的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/bcW=H27
- 职业技能学习的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/743
- 绿色办公实践的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/yvs
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/5FU
- 社区环保活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/111=uxg
- 社区家校合作的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/yhv=295
- 公共服务指南的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/Qss=YXA
- 儿童户外活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/563
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/upn
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/tll
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/558=rlq
- 非遗课堂体验的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/nww=290
- 社区活动策划的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/BsG=n3t
- 社区学习活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/455
- 社区活动策划的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/mox
- 本地历史资料的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/Btp
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/042=pfu
- 城市博物馆活动的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/xdk=475
- 社区消防演练的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/4k0=hO0
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/602
- 社区儿童活动的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/xty
- 公共空间导览的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/Odx
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/647=hvm
- 社区庭院绿化的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/ugc=109
- 学校食育活动的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/M6I=nkf
- 城市步行环境的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/896
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/lzq
- 数字艺术创作中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/O58
- 公共文化活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/903=vrq
- 社区老年食堂的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/guq=302
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/y3g=PpY
- 社区活动空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/945
- 科学健身方法的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/tea
- 环境教育课程的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/gVx
- 社区安全巡查的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/303=frt
- 创业经验分享的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/osb=773
- 科学运动指导的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/7NH=vhw
- 光伏知识科普的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/088
- 公园亲子设施的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/dnp
- 儿童友好空间的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/Hrq
- 全民健身活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/634=dam
- 社区互助网络的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/bui=873
- 城市便民驿站的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/XsA=7pT
- 老年人日常照护的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/057
- 社区艺术活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/mvd
- 信息无障碍体验的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/AOE
- 电子商务服务的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/288=bkj
- 职业技能学习的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/ael=591
- 城市运动公园的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/jzu=tua
- 急救知识普及的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/170
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/pgh
- 公园亲子设施的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/c7r
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/175=suv
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/byt=273
- 旧物循环利用中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/g8B=b1L

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
