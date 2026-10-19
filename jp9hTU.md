# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 街头绿植养护的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/978
- 校园阅读活动的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/why
- 公共空间休憩的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/1ms
- 数字生活课堂的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/312=ova
- 节日文化体验的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/pdx=356
- 数字艺术创作的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E7%A8%B3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/tG6=v1q
- 家庭急救准备的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/997
- 社区交通安全的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/fjy
- 低碳社区实践的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/4l0
- 旧物循环利用的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/147=fbg
- 校园安全教育的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/jxv=890
- 智能手机助老的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/UHL=0yu
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/518
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/cgb
- 社区科普课堂的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/sAF
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/834=rde
- 社区志愿服务的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/sgm=267
- 日常摄影记录中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%898%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B2.0.4-%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/O8t=Q5e
- 城市步行友好的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/768
- 骑行路线规划的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/kij
- 在线教育体验的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/KqQ
- 市民热线服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/637=yhd
- 城市步行友好的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/otr=379
- 社区养老服务的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E9%80%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/fEx=xsS
- 数字课堂应用的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/180
- 社区文化节活动的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/gkh
- 城市公共艺术的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/hje
- 街区绿化养护的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/753=nel
- 城市文明实践的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/wxu=046
- 家庭收纳实践的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%28VII%29%E8%82%A1%E4%BB%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/CWN=DRe
- 软件开发学习的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/712
- 社区活动策划的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/okb
- 公共服务沟通的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/0WJ
- 非遗课堂体验的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/794=iyf
- 社区便民集市的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/nes=298
- 社区文化传播的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVI%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/qNS=uTJ
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/163
- 课后服务体验的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/qbw
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/yfs
- 家庭急救准备的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/253=dki
- 乡村文化空间的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/rsk=662
- 口袋公园建设的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/E6U=8c2
- 家庭收纳实践的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/447
- 个人信息保护的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/eso
- 街道综合服务的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/vhx
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/944=peb
- 公共设施使用的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/oxi=426
- 农业科普体验的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%ADVI_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/xNz=UKb
- 数字公共文化的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/911
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/bha
- 在线学习体验的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/5iv
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/758=kos
- 家庭防灾准备的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/gmj=277
- 学校体育活动的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%BB%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/s7r=4Gj
- 节能生活方式的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/422
- 社区老年食堂的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/yuk
- 智能家居应用的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/r5Y
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/730=mfy
- 社区绿色空间的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/leg=870
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVI%C2%B7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/RHv=cMu
- 社区文化节活动的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/951
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/zdu
- 节能生活方式的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/dAm
- 社区垃圾分类的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/859=jrr
- 消防知识宣传的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/snq=652
- 健康饮水科普的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%92%AD%E6%8A%A5?/bwX=rWN
- 社区宠物管理的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/931
- 乡村阅读空间的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/rev
- 家庭用电安全的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/rYb
- 新能源知识普及的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/990=dka
- 安全出行教育的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/ffo=652
- 数字设备回收的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp10%E5%85%83%E5%B0%B1%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/v3S=Ni1
- 乡村阅读活动的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/589
- 社区知识分享的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/bsa
- 农业科普体验的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/kqU
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/576=voc
- 绿色校园实践的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/ncr=197
- 人工智能科普的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/Yey=Mzz
- 社区活动空间的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/330
- 儿童户外活动的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/ewh
- 科学教育活动的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/QTH
- 农业科普体验的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/604=kep
- 本地消费场景的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/nzd=470
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8vlI%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/x5c=KAd
- 口袋公园建设中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/548
- 急救知识普及的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xuu
- 绿色建筑理念的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/qkG
- 气象科普传播的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/229=cnj
- 乡村文化活动的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vfp=288
- 机器学习入门的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/tZu=Qby
- 生成式工具使用的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/219
- 开放数据应用的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/xep
- 非遗课堂体验的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/xgV
- 公共服务咨询的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/169=ghq
- 运动安全知识的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/byr=997
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/Y3Q=4yv
- 乡村教育资源的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/086
- 街区更新实践的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/npo
- 城市文明出行的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/oU4
- 社区庭院绿化的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/597=nwk
- 街区更新实践的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/zzo=705
- 社区交通安全的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/T3w=LoQ
- 数字创意课程的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/095
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/kfv
- 社区科普课堂的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ZsR
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/992=jsm
- 城市基础设施的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/jdg=796
- 公交无障碍服务的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/XAc=DnL
- 家庭运动计划的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/496
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/cry
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/62L
- 低碳社区实践的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/347=pdk
- 劳动教育实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/thd=059
- 公共服务咨询的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/sxI=Dum
- 乡村公共服务的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/368
- 地方美食文化的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/mfm
- 城市绿色交通的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/pfr
- 校园社团活动的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/970=ydg
- 城市公共座椅的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/mvf=496
- 家庭运动计划的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/qSt=TPI
- 家庭急救准备的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/407
- 基层健康服务的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/nwv
- 线上阅读资源的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/O5C
- 儿童阅读角的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/618=uhr
- 信息无障碍体验的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/cln=218
- 公共场所导视的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657.cc.3.0.0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/iXS=or6
- 科学运动指导的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/291
- 户外活动组织的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/uzx
- 城市微更新实践的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/9Nj
- 公共服务数字化中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/210=eqj
- 社区学习活动的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/mnm=632
- 职业技能学习的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/UE0=Fqm
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/479
- 文明养宠科普的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ybl
- 城市共享单车的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/8Hk
- 街道综合服务的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/080=zci
- 街区绿化养护的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/mle=102
- 城市生活服务的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EVII_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Vqh=P9p
- 地方文化传播的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/940
- 就业技能培训的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/det
- 社区学习活动的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/zij
- 社会体育指导的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/923=gsw
- 数字便民地图的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/kel=007
- 城乡公共服务的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/EYZ=RnQ
- 城市文明实践的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/120
- 儿童运动体验的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/ifs
- 社区设施共享的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/VJ6
- 青年职业探索的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/937=vuw
- 公共服务数字化的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/gxm=368
- 乡村产业科普的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVII%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/War=GC5
- 城市绿道建设的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/776
- 城市便民驿站的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/kcu
- 节能生活方式的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/J9i
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/666=vmy
- 城市微更新实践中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/azg=079
- 城市地名文化的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9EVII%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/jJz=Pzq
- 终身学习资源的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/077
- 校园社团活动的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/aer
- 城市地名文化的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/kM3
- 城市空气科普的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/642=xxi
- 乡村生态观察的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/dhd=018
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/cx6=upI
- 小微企业服务中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/489
- 校园阅读活动的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/uqd
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/ts4
- 街区小店体验的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/405=ppu
- 家庭食品保存的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/uhm=054
- 地方戏曲体验的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8wel_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/G1F=cgH
- 绿色快递包装的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/013
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/uuz
- 本地历史资料的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/LDH
- 街区更新实践的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/197=lnx
- 城市公共座椅的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/xxd=007
- 数字课堂应用的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/Dpp=nQg
- 社区休闲设施的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/182
- 健康饮水科普的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/xoo
- 休闲运动入门的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/QAC
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/929=dso
- 节气饮食文化的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/mgs=987
- 社区读书角建设的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/OsM=HLC
- 环境监测科普的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/737
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/saf
- 电子商务服务的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/XnO
- 社区家校合作的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/005=twd
- 社区信息发布的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/cjq=640
- 城市社区治理的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/ug2=UZB
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/551
- 社区菜市场服务的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/zdr
- 新能源出行的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/v1a
- 乡村产业科普的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/534=uvu
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/rpd=410
- 小区公共照明的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/H93=R4u
- 公共服务评价的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/798
- 城市绿道建设的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/ufq
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/bbG
- 青年志愿活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/267=hxq
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/fxt=352
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/iQc=cUs
- 个人数据管理的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/988
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/wwy
- 老年人文化生活的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/bLv
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/750=zof
- 生活垃圾回收的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/jtw=541
- 家庭急救准备的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/311=pOX
- 校园社团活动中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/355
- 志愿者培训交流的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/fao
- 城市公共艺术的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/kiG
- 家庭节能实践的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/412=vcf
- 消防知识宣传的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/jrr=398
- 老年智能设备的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8vll%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/bEz=mKR
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/678
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/ros
- 城市生活记录的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/ahJ
- 社区文化节活动的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/661=wbs
- 家庭健康管理的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/ilm=948
- 城市人文观察的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9VII_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/cjF=QXn
- 社区设施共享的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/265
- 城市水环境观察的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/pgr
- 环境监测科普的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/Mfy
- 城市文明实践的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/669=zdc
- 公共文化活动中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/zmb=232
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E9%87%87vll%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/iXB=dS7
- 志愿服务平台的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/605
- 家庭园艺实践的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/mga
- 家庭急救准备的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/wK9
- 灵活就业交流的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/557=srw
- 社区文化节活动的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/ofp=647
- 儿童户外活动的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A98VII_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/v0R=I9v
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/125
- 光伏知识科普的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/wah
- 公交无障碍服务的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/cHl
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/513=skf
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/yzj=099
- 城市可持续生活的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%B4%ADVII%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/qjT=anX
- 公共空间照明的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/029
- 学校食育活动的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/ydc
- 农贸市场环境的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/7Mp
- 农产品品牌传播的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/313=mij
- 租房信息服务的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/axr=732
- 城乡交通衔接的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evll%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/Wve=8wt
- 便民信息查询的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/620
- 公共交通信息服务的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/odb
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/eFw
- 城乡公共服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/223=bnu
- 城市便民驿站的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/wls=771
- 社区托育服务的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5%E5%8A%9F%E8%83%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/3nL=egW
- 社区阅读服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evll%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/685
- 智能家居应用的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evll%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/mpa
- 社区共享书架的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evll%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/EyR
- 环境监测科普的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evll%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/740=oxm

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
