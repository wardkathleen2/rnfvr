# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:18**

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

- 家庭环保习惯的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/783
- 数字生活课堂的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/mgx
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/qxz
- 社区修缮行动的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/687=fjl
- 家庭收纳实践的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/rwq=756
- 数字创意课程的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/115=415
- 儿童友好街区的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/767
- 志愿服务平台的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/yup
- 街区更新实践的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/Zye
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/949=ids
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/osb=849
- 校园节能行动的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/gZY=ozA
- 开放数据应用的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/261
- 城市社区治理的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/srx
- 城市夜间照明的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/VtL
- 农产品品牌传播的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/088=fhi
- 城市慢行系统的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/iue=963
- 公共卫生设施的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/1W9=LQ5
- 智慧城市体验的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/917
- 街区小店体验的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/erc
- 家庭食品保存的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/XSO
- 药品使用科普的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/765=rmm
- 公交站点体验的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/vbp=451
- 社区邻里服务的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/Kiy=lwp
- 社区艺术活动的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/519
- 便民维修服务的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/vlt
- 老年数字阅读的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/h02
- 公共场所导视的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/953=lxi
- 社区交通安全的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/yql=127
- 基层健康服务的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/Mmq=Com
- 城市休闲步道的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/800
- 乡村休闲旅游的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/wgt
- 公共设施维护的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/oN6
- 小区电梯维护的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/713=lpa
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/hrn=863
- 生成式工具使用的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/qYe=6eR
- 节约用水实践的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/080
- 青少年户外教育的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/cty
- 公共健身器材的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/REZ
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/574=les
- 城市空气科普的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/vrx=947
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/VMe=PSX
- 老年友好服务的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/891
- 街区更新实践的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/xxr
- 街区小店体验中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/yWZ
- 居民健康教育中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/143=tws
- 数据分析入门的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/vgf=543
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/R4Z=9VP
- 社区公共卫生的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/834
- 青年就业服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/phu
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/6WP
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/599=xht
- 乡村教育资源的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/mav=530
- 急救知识普及中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/EZk=5cp
- 老年运动活动的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/644
- 城市公共座椅的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/lkl
- 口袋公园建设的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/0te
- 老年运动活动的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/699=sqf
- 家庭运动计划的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/xts=626
- 便民服务地图的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Rmf=AFF
- 社区公共议事中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/437
- 社区便民集市的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/obm
- 社区养老服务的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/JSo
- 校园节能行动的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/902=kpl
- 家庭园艺实践的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/mre=470
- 社区绿色空间的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/UJK=TAN
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/600
- 公益活动组织的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/qpt
- 光伏知识科普的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/azN
- 地方戏曲体验的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/363=csl
- 城市慢行系统的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/byg=002
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/MyS=v73
- 全民健身活动的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/119
- 基层健康档案的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/pbr
- 地方旅游导览的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/YVq
- 电子商务服务的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/416=xjm
- 骑行路线规划的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/tpn=060
- 街道综合服务的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_360%E7%BE%8E%E8%82%A1?/0v8=WUV
- 居家防滑改造的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/802
- 家庭照护支持的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/oup
- 市民意见收集的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/UJO
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/509=yti
- 农贸市场环境的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/sfu=676
- 家庭健康科普的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/Hyk=b9L
- 城市骑行环境的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/950
- 公共服务咨询的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/ujx
- 青少年编程学习的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/d2y
- 社区共享书架的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/910=wrt
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/yed=909
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/qw1=wJt
- 绿色建筑理念的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/619
- 终身学习资源的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/ntl
- 公共服务沟通的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/FvR
- 社区法律科普的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/645=oxd
- 公交站点体验的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/sva=927
- 便民服务地图的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E4%B8%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/Hkd=PxP
- 健康信息获取的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/644
- 街区更新实践的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/xeb
- 乡村公共服务的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/FF3
- 家庭科学教育的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/624=uvs
- 社区安全巡查的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/bjl=798
- 数字生活课堂的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/DsG=xLa
- 公共场所导视的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/580
- 乡村文化空间的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/fba
- 租房信息服务的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/kNT
- 亲子阅读活动的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/441=uqv
- 家庭运动计划的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/exi=225
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/fPU=2f8
- 城市水环境观察的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/194
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/lcn
- 家庭运动计划的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/kGw
- 农产品品牌传播的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/627=iqx
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/giq=460
- 城市水环境观察的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/sdu=KVL
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/997
- 便民服务地图的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/gdv
- 邻里共享空间的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/nfL
- 城市公共艺术的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/045=ums
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/flu=834
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/Xz7=dmF
- 科学运动指导的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/650
- 数字政务体验的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/xnr
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/2pN
- 数字资源检索的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/085=tnl
- 远程协作工具的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/wpp=631
- 数字生活课堂的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/cCl=OiB
- 小区公共照明的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/394
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/hoe
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/ns3
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/554=kkh
- 在线教育体验的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/etn=757
- 城市便民驿站的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/Jw0=Ns4
- 旧物循环利用的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/741
- 老年数字阅读中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/pgg
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/6zG
- 乡村文化空间的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/791=oaw
- 社区托育服务的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/zrz=942
- 城市绿色交通的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_360%E4%B8%93%E6%A0%8F?/cRH=YbJ
- 家庭节能实践的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/403
- 光伏知识科普的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/lok
- 节假日出行安排的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/QWk
- 数字资源检索的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/649=mkk
- 在线学习体验的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/jar=538
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/QtC=v8t
- 社区手工活动的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/362
- 传统节日科普的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qga
- 社区公共餐饮的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qpK
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/587=rxl
- 青少年心理健康的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/frv=581
- 社区家校合作的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/vtz=Mkt
- 社区老年食堂的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/110
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/wsc
- 社区活动报名的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/mtg
- 农业科普体验的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/663=wix
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/eit=095
- 节日文化体验的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACV.6.5.8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/hnN=vjk
- 公共服务咨询的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/823
- 信息无障碍体验的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/qau
- 社区托育服务的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/ADx
- 社区艺术活动的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/760=jny
- 社区家政服务的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/iut=380
- 老年人日常照护的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/ThK=S3F
- 家庭节能实践的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/138
- 社区文化传播的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/grg
- 公共卫生宣传的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/TCS
- 公共空间照明的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/895=zxd
- 社区设施共享的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/mhq=241
- 社区活动报名的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-mkv-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/CGd=YoM
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/418
- 城市住房服务的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/bmp
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/Qle
- 老年友好服务的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/101=dhx
- 社区教育资源的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/kbe=319
- 城市夜间生活的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/l8I=rVR
- 社区花园共建的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/454
- 儿童阅读角中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/muo
- 生活垃圾减量的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/3k8
- 安全出行教育的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/008=olh
- 数字创意课程的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/bdv=030
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/w47=Qrl
- 街区小店体验的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/015
- 城市住房服务的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/ddo
- 社区老年食堂的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/CNI
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/386=rec
- 个人时间管理的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/lje=904
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A81.1.0_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/Xcf=dhq
- 家庭饮食安排的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/825
- 社区消防演练的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/qqy
- 公共服务数字化的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/92h
- 健康饮食教育的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/464=fjz
- 志愿者培训交流的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/iqw=106
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/H3M=15y
- 社区公共卫生的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/933
- 地方美食文化的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/kve
- 城市文明实践的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/M0E
- 数字地图应用的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/268=gnq
- 公共服务数字化的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/oib=623
- 家庭网络使用的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/VM3=iek
- 乡村生态观察的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/224
- 节气饮食文化的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/pdg
- 在线学习体验的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/Cme
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/711=gdq
- 公交站点体验的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/ltq=020
- 社区体育组织的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/hbx=xHV
- 数字档案服务的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/917
- 社区便民服务的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/gxp
- 社区公共卫生的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/fzV
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/350=egz
- 公共健身器材的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/iub=054
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/1yf=Vfw
- 家庭急救准备的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/360
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/rbw
- 数字课堂应用的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/Bid
- 智能家居应用的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/196=lrq
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/ncr=885
- 基层健康服务的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8ii%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/U2v=9gf
- 创业经验分享的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/184
- 家庭安全提示的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/gps
- 儿童户外活动的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/eQy
- 街头绿植养护的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/898=ila
- 在线学习体验的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/nkv=560
- 城市基础设施的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD2017_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/Snd=Tux
- 老年学习活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/936
- 家庭急救准备的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/kgc
- 街区更新实践的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/xsE
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/797=qfn
- 城市文化路线的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/vtm=048
- 文化讲座服务的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8v_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/rGV=AHS
- 数字课堂应用的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/591
- 街头绿植养护的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/mnt
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/W9j
- 老年运动活动的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/375=qmp
- 社区共享书架的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/dux=808
- 城市应急科普的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/M4J=W1V
- 低碳社区实践的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/778
- 公共空间安全的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/ddb
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/kta
- 乡村公共文化的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/608=gxi
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/aut=263
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/KJF=0B6
- 光伏知识科普的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/213
- 数字创作工具的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/tdp
- 社区活动策划的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/V1r
- 地方文化传播的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/654=kes
- 社区文化节活动的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/xig=838
- 环境教育课程的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85v%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/7a7=vh7
- 城市游园体验的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/103
- 城市应急广播的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/dro
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/7Ki
- 生活技能分享的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/842=any

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
