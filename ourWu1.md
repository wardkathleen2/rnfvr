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

- 社区托育服务的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8app%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/1jC
- 数字设备回收的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8app%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/219=zeh
- 城市地名文化的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8app%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/bss=727
- 线上办事服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8app%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/k99=o2R
- 公共空间休憩的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/934
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/auu
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/yIm
- 乡村文化空间的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/550=vtt
- 基层服务创新的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/pah=588
- 城市生活记录的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B4%A2%E7%BB%8F?/VqD=uo3
- 数字生活课堂的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/790
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/ahx
- 青少年心理健康的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/BFi
- 日常摄影记录的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/044=trz
- 科学观察活动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/nyk=389
- 家庭志愿活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E6%8A%95%E6%B3%A8_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/OvL=Ar2
- 社区公共卫生的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/370
- 通勤路线规划的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/gzk
- 家庭园艺实践的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/TwA
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/531=obu
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/fvb=707
- 急救知识普及的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/ePW=Qp5
- 公共空间休憩的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/655
- 农村环境治理的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/jyk
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/Qmf
- 邻里共享空间中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/462=lgc
- 社区消防演练的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/yfu=227
- 城市噪声观察的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/M1v=3A1
- 城市休闲步道的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/481
- 骑行路线规划的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/vfq
- 老年人文化生活的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/ZvV
- 健康步道使用的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/744=ver
- 城市社区治理的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/ioq=572
- 绿色办公实践的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/os3=RLD
- 社区交通安全的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/752
- 医院导诊服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/mox
- 家庭养老规划的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/tVU
- 小区电梯维护的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/146=gxz
- 儿童安全出行的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/ewh=739
- 科学教育活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/4Zj=SoQ
- 数字便民地图的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/272
- 校园节能行动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/jqk
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/yJ2
- 地方民俗记录的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/847=yhy
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/bpp=572
- 城市公共座椅的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/tyN=AgP
- 社区商业活力的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/019
- 公共健身器材的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/ljg
- 社区活动报名的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/kjf
- 家庭环保行动的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/675=pkk
- 乡村公共文化的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/mbw=408
- 开放数据应用的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%8C%85%E8%B5%94%E7%9F%A9%E9%98%B5%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BF%A1%E8%B4%B7?/KiT=Vw5
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/318
- 日常摄影记录的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/lyu
- 数字便民地图的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/GWK
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/919=klq
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/vhy=433
- 社区活动空间的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/EzU=xkw
- 公共服务咨询的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/581
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/jwb
- 家庭饮食安排的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/dKq
- 开放式学习空间的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/412=jjw
- 绿色消费选择中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/ens=941
- 乡村文化活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/2ZX=mW4
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/806
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/nor
- 社会体育指导的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/C67
- 公共交通信息服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/720=pux
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/qab=132
- 社区活动报名的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/eAZ=nIf
- 传统节日科普的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/479
- 口袋公园建设的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/esf
- 社区科普课堂的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/hOZ
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/650=lfv
- 口袋公园建设的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/bqc=540
- 灵活就业交流的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/5VG=Jda
- 公园休闲体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/130
- 图书馆活动策划的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/iwd
- 乡村文化活动的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/4pR
- 社区文化传播的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/240=ukq
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/nhr=277
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/1PN=5zd
- 城市可持续生活中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/368
- 社区科普课堂的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rmi
- 急救知识普及的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/N3t
- 老年运动活动的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/127=fws
- 光伏知识科普的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bnk=210
- 社区活动策划的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yow=6sq
- 城市地名文化的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/964
- 骑行路线规划的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/wuc
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/C1P
- 乡村产业科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/243=fte
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/eeq=025
- 校园社团活动的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2?/amq=HJl
- 农产品品牌传播的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/028
- 便民服务窗口中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/bkf
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/kiC
- 社区艺术活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/397=wxe
- 公共设施维护的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/ped=106
- 城市展览体验的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/P8U=u1K
- 数字艺术创作的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/719
- 儿童运动体验的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/daz
- 城乡交流活动的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/rDg
- 老年友好服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/211=ail
- 公益活动组织的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/iox=270
- 社区体育组织的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/6uG=WsK
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/852
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/mbm
- 开放数据应用的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/vOk
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/717=gdx
- 城乡交流活动的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/plx=670
- 市民意见收集的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E4%BF%A1%E6%89%98?/VoP=28m
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/089
- 城市生活记录的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vkm
- 城市空气科普的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/YSM
- 数字公共文化的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/148=pma
- 本地消费场景的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jqs=868
- 读书会组织的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eXV=mmG
- 社区学习活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/465
- 社区协商议事的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/bik
- 新能源知识普及的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/Ujx
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/245=wgc
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/jpf=066
- 社区活动空间的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/5rD=mNa
- 青少年编程学习中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/928
- 节假日出行安排中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/lwa
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/rxR
- 数字创作工具的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/114=cxe
- 儿童安全出行的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/qkl=488
- 乡村文化活动的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-a-p-p_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/2Wq=dvG
- 医院导诊服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/820
- 青年志愿活动的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/fzc
- 开放式学习空间的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/ycx
- 亲子科普活动的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/873=eqx
- 家庭急救准备的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/mxu=771
- 节能生活方式的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/YLp=JH3
- 数字生活课堂的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/452
- 街区更新实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/vef
- 创业经验分享的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/ZdY
- 社区活动报名的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/847=zwq
- 新能源出行的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/vsv=486
- 数字便民地图的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/6x6=08C
- 绿色出行服务的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/863
- 数字档案服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/iur
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/Pml
- 居民健康教育的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/897=tgp
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/eti=074
- 街区小店体验中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/v80=jSq
- 地方旅游导览的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/202
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/rnm
- 传统手工艺体验的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/H5f
- 数字阅读服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/675=lgd
- 社区公共卫生的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/ndf=652
- 社区安全巡查的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%8B%E7%BB%8D_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/Po3=Tpu
- 科普展览体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/430
- 城市公共空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/qij
- 基层服务创新中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/uek
- 儿童阅读角的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/094=tmi
- 社区环保活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/bwu=571
- 文化场馆预约的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/0bN=TdD
- 社区绿色空间的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/270
- 新能源出行从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/osi
- 低碳社区实践的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/yzF
- 邻里共享空间的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/140=bst
- 街道综合服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/mfq=567
- 基层健康服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%AF%E4%BB%98%E5%AE%9D%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/KlJ=uIg
- 本地消费场景的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/252
- 环境教育课程的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/rrw
- 智能家居应用的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/sSb
- 本地旅行体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/835=nvc
- 社区垃圾分类的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xca=666
- 邻里共享空间的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/OWl=Xro
- 地方文化传播的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/478
- 社区信息发布的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/sii
- 绿色快递包装的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/tll
- 绿色出行服务的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/524=bpo
- 城市建设科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/olr=694
- 无障碍信息设计的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/fdt=qRF
- 社区志愿服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/347
- 青年就业服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/ind
- 城乡交流活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/Ndl
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/034=ldf
- 家庭网络使用的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/crp=353
- 健康饮食教育的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/n73=yYE
- 城市绿色交通中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/935
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/shv
- 科普展览体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/hMm
- 线上办事服务的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/186=qkq
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/tin=119
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/poK=pae
- 青年职业探索的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/370
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/his
- 公交站点体验的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/vWM
- 社区家政服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/070=zny
- 城市文明出行的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/ora=621
- 社区生活指南中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%9D%A0%E8%B0%B1%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/ZPl=jG8
- 公共服务数字化的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/465
- 环境教育课程的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/jlf
- 口袋公园建设的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/wzJ
- 乡村教育资源的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/198=oys
- 邻里互助活动的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/aha=641
- 读书会组织的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/ORc=iQt
- 健康步道使用中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/459
- 药品使用科普的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/urr
- 志愿服务平台的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/xmU
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/315=fcr
- 社区便利生活的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/bwj=953
- 家庭消费规划的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/FRw=OZJ
- 基层服务创新的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/370
- 城市文明实践的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/krv
- 急救知识普及的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/742
- 社区家校合作的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/063=rsn
- 社区手工活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/fan=864
- 青少年心理健康的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/v4t=pzg
- 节日文化体验的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/668
- 绿色快递包装的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/ccr
- 就业技能培训的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/q0T
- 城市生活记录的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/791=tju
- 青少年户外教育的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/fxp=669
- 城市游园体验的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/Dbj=lFh
- 数字便民地图的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/908
- 生活服务数字化的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/kuw
- 公共空间休憩中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/gyn
- 城市骑行环境的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/563=iyq
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/xdz=144
- 科学运动指导的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/Ng6=EgG
- 公共服务数字化的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/874
- 城市公共厕所的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/yaw
- 社区托育服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/WLp
- 职业技能学习的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/882=hzs
- 乡村公共文化中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/qne=496
- 乡村电商实践的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/76Z=hiZ
- 科学教育活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/130
- 本地历史资料的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/mbv
- 网络安全教育中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/aSs
- 邻里互助活动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/108=mfh
- 社区商业活力的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/pwy=387
- 社区消防演练的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%A4%A9%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/QIH=92L
- 图书馆数字服务的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/332
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/hsp
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/3Kk
- 数字资源检索的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/042=hjh
- 城市文化路线的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/dyd=067
- 公共设施维护的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E6%9C%80%E7%89%9B%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/zeD=noR
- 机器人科普活动的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/301
- 就业技能培训中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/mhg
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/Eg4
- 个人时间管理的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/009=mtx
- 健康饮食教育的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/ssv=271
- 城市水环境观察的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/Zvf=CfZ

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
