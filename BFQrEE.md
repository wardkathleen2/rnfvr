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

- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/348
- 社区养老服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/ixs
- 城市基础设施的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/Vhp
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/287=mdd
- 社会体育指导的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/eck=487
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/2GN=fli
- 地方文化传播的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/547
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/jjr
- 社区家校合作的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/Vtf
- 城市公共艺术的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/586=mzb
- 社会体育指导的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/pfj=843
- 数字公共文化的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/EVd=GYG
- 公共空间安全中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/510
- 乡村电商实践的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/blq
- 急救知识普及的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/xoB
- 城市文明出行的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/813=egw
- 公共服务沟通的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/myw=569
- 光伏知识科普中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/2nX=MjS
- 城市建设科普的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/444
- 社区老年食堂的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/sqo
- 户外活动组织的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/oM1
- 城市微更新实践的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/873=xzo
- 数字艺术创作的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/zfu=210
- 社区信息发布的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/vhB=SML
- 街区道路维护的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/237
- 终身学习资源的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/xfv
- 社区读书角建设的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/fOb
- 公共健身器材的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/333=zpr
- 全民健身活动的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/cde=494
- 城市树木认养的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/LJ0=XJu
- 环境教育课程的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/111
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/eyw
- 公益活动组织的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/JNA
- 公共卫生设施的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/298=hlu
- 老年人文化生活的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/pie=421
- 租房信息服务的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E5%92%8C%E5%80%BC%E7%9A%84%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/nXv=wVY
- 学校体育活动的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/700
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/vtb
- 智能家居应用的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/q0h
- 文明养宠科普的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/594=ukb
- 社区停车服务的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/qtn=901
- 节能生活方式的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%89%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/4eZ=i35
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/284
- 社区信息发布的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/fzg
- 绿色消费选择的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/4xy
- 医院导诊服务的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/458=zcx
- 数字政务体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/yna=504
- 旧物循环利用的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/X75=wMm
- 城市公共空间的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/127
- 社区手工活动的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/qga
- 本地消费场景的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/nl6
- 非遗体验活动的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/357=ovx
- 个人时间管理的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/moa=949
- 家庭安全提示的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/PNH=rOy
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/347
- 小区电梯维护的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/edv
- 社区生活指南的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/UDY
- 数字政务体验的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/961=hvj
- 就业技能培训的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vas=005
- 文化讲座服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/5Rn=9Bu
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/177
- 家庭健康管理的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/qjs
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/XYg
- 家庭园艺实践的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/523=hbo
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/lnk=005
- 城市文化路线的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/FxW=jQD
- 老年人出行服务的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/797
- 社区便民服务的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/sbt
- 新能源出行的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/O4n
- 社区便民服务的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/288=fvg
- 儿童户外活动的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/yck=833
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/y3c=mxY
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/754
- 绿色消费选择的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/qax
- 个人信息保护的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/PQs
- 家庭运动计划的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/008=fnb
- 社区心理支持的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/onp=690
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%9A%84%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/JUW=HLg
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/027
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/iqy
- 公园休闲体验的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/6yQ
- 跨代沟通活动的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/986=orz
- 生活垃圾减量的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/lax=023
- 社区法律科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_Welcome-%E5%B9%B8%E8%BF%90%E4%B8%89%E5%88%86%E5%BF%AB3_%E8%B4%A2%E7%BB%8F?/oZn=0td
- 城市骑行环境的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/764
- 数字生活课堂的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/rkx
- 社区垃圾回收的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/mJd
- 青年就业服务的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/163=zee
- 青少年编程学习的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/ofu=670
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/oLz=JZ9
- 公园休闲体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/404
- 社区垃圾分类的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/nsa
- 家庭网络使用的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/RE4
- 周末休闲规划的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/168=nqh
- 全民阅读推广的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fwy=655
- 城市便民驿站的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/4Vr=eHS
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/688
- 应急物资管理的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mgq
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xwX
- 社区防暑服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/073=ghj
- 社区便民集市的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/cdo=043
- 城市游园体验的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/5W9=Jhh
- 社区教育资源的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/686
- 社区设施共享的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/kmm
- 城市基础设施的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/RP6
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/325=zxo
- 城市公共厕所的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/trz=967
- 公共场所导视的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/IzM=lcW
- 城市步行友好中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/085
- 社区心理支持的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/hsz
- 旧物循环利用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/Kza
- 健康饮食教育的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/168=cgf
- 城市步行友好的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/ddr=837
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/rOj=eNn
- 公共设施使用的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/670
- 社区公共卫生的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/svz
- 安全出行教育的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/vy9
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/812=nib
- 绿色出行服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/xtu=850
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/6nn=yFO
- 城市绿色交通的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/549
- 公共场所导视的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/tlo
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/lm1
- 小微企业服务的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/425=nze
- 乡村教育资源的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/aka=635
- 地方民俗记录的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/jxA=mi1
- 电动汽车充电的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/534
- 老年友好服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/vvx
- 儿童运动体验的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/MWp
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/211=nxi
- 社区共享书架的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/muj=159
- 课后服务体验中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/dQF=qlo
- 城市可持续生活的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/098
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/hxw
- 图书借阅体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/jWT
- 数字创作工具的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/263=lpj
- 家庭健康科普的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/dwe=314
- 传统手工艺体验的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/4Ot=ja5
- 本地消费场景的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/922
- 社区便民服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/pcf
- 公共空间休憩的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/PhA
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/129=ipa
- 数字阅读服务的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/sgo=561
- 城市雨天出行的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/Qga=4Bi
- 文化讲座服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/496
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/cht
- 农业科普体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/IKw
- 小微企业服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/599=qqf
- 电动汽车充电的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/oob=932
- 科学教育活动的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BA%94%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_360%E8%A1%8C%E6%83%85?/rLl=Kyo
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/108
- 社区协商议事的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/dvu
- 公益活动组织的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/U61
- 城市文明出行的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/723=nkx
- 远程协作工具的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/uuf=473
- 社区修缮行动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_5%E5%88%86pk10%E6%8E%A8%E7%AE%97_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/bPg=83e
- 城市农夫市集的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/029
- 家庭环保习惯的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/oke
- 软件开发学习的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fE2
- 社区便民服务的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/651=apq
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xhl=758
- 农业科普体验的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/IRc=x1e
- 青少年心理健康的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/531
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/nke
- 城乡公共服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/uWB
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/471=pxi
- 远程协作工具的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/tbf=510
- 数字政务体验的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/P8P=6My
- 城市生活服务的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/069
- 社区修缮行动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/kqh
- 社区法律科普的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/YOz
- 家庭照护支持的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/577=ptr
- 家庭运动计划的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vmr=684
- 公共设施维护的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/jo6=Lw6
- 青少年编程学习的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/023
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/ogu
- 旧物循环利用的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/dlS
- 社区故事采集的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/737=phr
- 家庭阅读计划的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/ytv=984
- 食品安全科普的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/k4S=GsZ
- 街区道路维护的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/541
- 本地消费场景的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/evx
- 生活垃圾减量的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/1Jf
- 社区文化节活动的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/565=afr
- 绿色生活实践的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/niu=862
- 个人信息保护的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/AiF=uki
- 乡村公共文化的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/851
- 家庭教育交流的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/xpl
- 药品使用科普的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/c04
- 乡村文化活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/874=reh
- 青少年心理健康的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/vrp=145
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_5%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/2ie=0CU
- 乡村教育资源的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/336
- 家庭节能实践的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/vgy
- 物业服务沟通的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/KR3
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/647=mcr
- 家庭科学教育的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/gsp=017
- 食品安全科普的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/cLt=vJI
- 儿童运动体验的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/073
- 青年职业探索的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/khm
- 公共交通接驳的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/yQG
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/284=lga
- 城市公共标识的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/cij=467
- 城市应急科普的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/B4v=Sfm
- 人工智能科普的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/842
- 生活垃圾回收的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/sua
- 家庭用电安全的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/qRk
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/138=yom
- 智慧城市体验的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/tho=825
- 公共空间休憩的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/qMi=4h4
- 公共文化活动的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/166
- 老年学习活动的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/uzh
- 公共空间休憩的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/H2z
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/615=lec
- 非遗课堂体验的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/txc=223
- 公共服务数字化的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/g5D=4aM
- 社区故事采集的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/808
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/xug
- 公共设施使用的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/cYH
- 地方旅游导览的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/424=uns
- 社区快递服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/nzr=187
- 公共场馆服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8D%8F?/eoB=kVy
- 公园亲子设施的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/109
- 线上办事服务的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/xlq
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/HUH
- 远程协作工具的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/634=kwn
- 线上办事服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/adh=256
- 本地消费场景的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Y9T=mwT
- 校园阅读活动的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/783
- 学校体育活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/fgr
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/wrx
- 智慧停车服务的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/778=vhh
- 智能手机助老的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/kth=258
- 街区更新实践的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A95%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/eVo=dSs
- 家庭收纳实践的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/068
- 本地消费场景的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/zgk
- 本地旅行体验的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/etI
- 社区儿童活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/687=hjo
- 医院导诊服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/idw=362
- 数字政务体验的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%A8%B1%E4%B9%90?/LJY=ADb
- 城市微更新实践中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/751
- 公共交通接驳的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/ekd
- 绿色出行服务的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/mI2
- 乡村公共服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/332=kru
- 开放式学习空间的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/wxi=103
- 课后服务体验的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/Nqd=IWV
- 数字课堂应用的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/704
- 节能家电使用的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/pjz
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/dBP
- 城市体育设施的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/862=zve

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
