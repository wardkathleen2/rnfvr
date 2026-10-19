# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:15**

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

- 城市水环境观察的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/fdh=088
- 安全出行教育的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/7WZ=fV1
- 公共文化活动中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/986
- 家庭网络使用的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/xkq
- 社区商业活力的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/14a
- 全民阅读推广的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/130=jqi
- 社区体育组织的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/cfp=534
- 公交站点体验中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/w7S=HJW
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/230
- 家庭运动计划的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/juh
- 本地消费场景的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/W50
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/049=dpm
- 小区停车协商的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/ses=579
- 社区活动空间的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/9hW=GHm
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/830
- 公共服务预约的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/dsn
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/asZ
- 社区休闲设施的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/542=lsc
- 城市社区治理的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/mfy=830
- 家庭消费规划的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/eeE=xaD
- 城市绿色交通的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/584
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/jeh
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/52w
- 城市游园体验的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/105=srk
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/ynq=867
- 老年人日常照护的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/6gf=QDr
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/526
- 公园休闲体验的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/aku
- 消防知识宣传的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/Urq
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/243=dur
- 机器学习入门的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/gop=034
- 节假日出行安排的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/sky=2mD
- 机器人科普活动的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/259
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/jad
- 城市生活记录的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/zo9
- 公共卫生设施的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/701=kvs
- 社区托育服务的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/joq=905
- 市民意见收集的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%98%9F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/Fdy=Te3
- 在线学习体验的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/977
- 读书会组织的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/irn
- 智能手机助老的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/e6i
- 应急物资管理的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/428=ahx
- 本地消费场景的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/fzp=803
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/TgF=S0y
- 城市绿色交通的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/519
- 生活服务数字化的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/zgt
- 城市住房服务的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/fbS
- 社区活动策划的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/646=tvv
- 居家防滑改造的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/ofm=749
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/Z8t=AoO
- 电子商务服务的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/224
- 在线学习体验的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/oec
- 家庭网络使用的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/gWS
- 社区科普课堂中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/262=vhy
- 家庭科学教育的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/ahl=811
- 开源技术交流的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/Elb=tYE
- 邻里互助活动的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/598
- 社区故事采集的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/sxh
- 周末休闲规划的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/2rV
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/340=awm
- 校园安全教育的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/gif=343
- 文明养宠科普的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%BF%B0%E8%AF%84?/64B=T8j
- 社区绿色空间的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/570
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/kmy
- 家庭收纳实践的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/XJs
- 校园社团活动的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/923=dnc
- 公共卫生设施的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/umz=553
- 农村环境治理的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/ogb=CIA
- 农产品消费体验的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/530
- 无障碍出行的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/qis
- 社区环保活动的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/KP7
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/698=vfs
- 乡村生活观察的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/pfu=340
- 健康步道使用的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/HOO=ymN
- 城市建设科普的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/300
- 老年人日常照护的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/nbm
- 科技馆参观体验的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/K6v
- 社区科普课堂的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/123=rdl
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/wsh=514
- 环境教育课程的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/aCx=aLf
- 基层健康档案的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/412
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/yip
- 全民健身活动的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/Dn8
- 绿色快递包装的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/873=sbw
- 社区文化节活动的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/dba=093
- 非遗体验活动的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8E%A2%E5%BA%97?/mUt=WBN
- 社区休闲设施的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/977
- 公益活动组织的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/pyg
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/YFI
- 图书馆数字服务的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/792=iyd
- 城市适老服务的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/pnb=648
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/vTa=NdP
- 社区养老服务的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/272
- 校园阅读活动的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/ini
- 城市应急科普的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/n3z
- 智能手机助老的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/848=ejt
- 健康饮食教育的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/xnr=331
- 家庭饮食安排的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/fqq=z5X
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/410
- 家庭健康科普的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rte
- 老年运动活动的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Kes
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/575=bns
- 公共设施维护的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ara=514
- 家庭运动计划的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/8uE=DMH
- 邻里共享空间的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/417
- 社区邻里服务的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/vut
- 课后服务体验的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/3xD
- 社区读书角建设的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/640=gzf
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/tgr=070
- 居家防滑改造的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/CM9=gnM
- 城市夜间照明的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/460
- 青少年户外教育的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/zdp
- 个人数据管理的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/sel
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/308=nkn
- 社区交通安全的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/rkl=207
- 乡村产业科普的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%AE%BF?/TzU=PZ0
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/297
- 医院导诊服务的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/mwv
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/NHt
- 城市空气科普的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/718=gxx
- 乡村文化空间的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/pmx=132
- 环境教育课程的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/f7j=eyM
- 学校食育活动的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/426
- 消防知识宣传的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/cxe
- 城市骑行环境中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/WIZ
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/934=qnf
- 新能源出行的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/guh=182
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/9Y3=jDh
- 环境教育课程的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/772
- 邻里互助活动的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/xmm
- 社区安全巡查的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/JZA
- 城市建设科普的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/165=kow
- 社区防暑服务的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/krk=411
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/2fB=Y9R
- 家庭安全提示的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/175
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/nby
- 社区阅读服务的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/a82
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/225=qsq
- 社区健康讲座中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/vwg=883
- 健康信息获取的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/LMR=h3t
- 社区法律科普的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/843
- 社区共享书架的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/rfi
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/RXM
- 运动安全知识的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/432=yfy
- 节气饮食文化的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/iha=536
- 社区商业活力的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/i1A=R8p
- 城市社区治理的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/503
- 机器人科普活动的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/ozu
- 数字设备回收的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/TkJ
- 公园休闲体验的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/303=zkb
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/pzb=733
- 家庭安全提示的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/b60=jBC
- 青年就业服务的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/581
- 新能源知识普及的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/vlz
- 社区读书角建设的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/gWD
- 社区快递服务的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/049=txo
- 安全出行教育的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/ufl=889
- 乡村生态旅游的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/QDG=xiD
- 城市应急广播的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/830
- 个人时间管理的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/jft
- 城市社区治理的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/mK0
- 家庭用电安全的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/793=gty
- 无障碍信息设计的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/byr=983
- 城乡交流活动的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/JTs=c6H
- 个人信息保护的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/376
- 文明养宠科普的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/tte
- 公共卫生宣传的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/QuS
- 远程协作工具的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/451=owm
- 社区垃圾回收的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/cup=780
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/pzn=zPl
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/988
- 街区小店体验的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/wjr
- 城市水环境观察的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/v0a
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/122=zlb
- 乡村文化活动的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/ydc=529
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/p0S=XTP
- 城乡公共服务的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/571
- 公共空间安全的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/btl
- 城市骑行环境的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/9c4
- 基层健康服务的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/803=gfb
- 社区健康讲座的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/olf=853
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/e5D=GRR
- 公共空间安全的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/741
- 城市微更新实践的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/ekr
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/XXV
- 城市夜间生活的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/362=iqd
- 全民健身活动的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/fwx=058
- 在线学习体验的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/mRx=ShF
- 开源技术交流的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/280
- 在线教育体验的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/ozb
- 城市步行友好的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/GKk
- 公共场所导视的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/775=izp
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/wol=078
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/cLz=j7O
- 网络信息辨识的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/931
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/mzc
- 学校体育活动的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/Bmt
- 社区便民服务的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/931=njs
- 非遗体验活动的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/ktt=629
- 社区邻里服务中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/Jcq=kH8
- 公共空间照明的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/015
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/wah
- 无障碍信息设计的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/Bjx
- 居民健康教育的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/584=kle
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/lyd=408
- 农产品消费体验的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/y9n=YmS
- 公园亲子设施的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/115
- 食品配送体验的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/gip
- 乡村阅读空间的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/mgO
- 农业科普体验的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/117=uzf
- 地方文化传播的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/riq=303
- 家庭消费规划的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/pVm=P0K
- 公共空间照明的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/875
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/avs
- 运动安全知识的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/y2e
- 乡村公共服务的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/788=tra
- 儿童友好街区的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/wkj=372
- 城市夜间生活的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/Ggs=3DI
- 数字政务体验的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/571
- 生活技能分享的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/csq
- 公共空间安全的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/08n
- 城市应急广播的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/443=nxd
- 家庭照护支持的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/brp=588
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/EgD=2Db
- 城市绿道建设的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/300
- 街区更新实践的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/uyg
- 小区电梯维护的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/a4U
- 户外活动组织中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/559=pkm
- 社区公共餐饮的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/fmz=483
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E8%A7%A3%E5%AF%86?/oHb=H6d
- 家庭用电安全的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/598
- 街区更新实践的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/zbc
- 无障碍出行的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/s6u
- 城市文化路线的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/009=vig
- 数字政务体验的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/qhq=168
- 社区修缮行动的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/ack=Rge
- 急救知识普及的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/289
- 通勤路线规划的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/awp
- 社区文化传播的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/6pF
- 青年就业服务的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/381=gak
- 日常摄影记录的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/akk=264
- 社区交通安全的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/aty=wRX
- 在线学习体验的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/452
- 智慧停车服务的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/pjg
- 城市博物馆活动的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/QHW
- 家庭志愿活动的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/169=hsa
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/pdl=178
- 科学教育活动的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/On6=RvE
- 居民健康教育的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/476
- 无障碍出行的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/hmv

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
