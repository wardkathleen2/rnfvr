# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 城市公共厕所的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BDios_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/lhm=509
- 城市文明出行的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BDios_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/jwr=EZ1
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/306
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/xst
- 数字阅读服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/mjs
- 垃圾分类指导的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/559=sag
- 儿童友好空间的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/osl=007
- 软件开发学习的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/T56=Y4P
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/232
- 城市步行环境的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/qao
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/s0N
- 乡村生活观察的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/350=xkl
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/mrf=277
- 开放数据应用的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F3d%E5%BD%A9%E7%A5%A81%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/7fL=bVr
- 社区活动报名的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/950
- 文化场馆预约的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/lqa
- 乡村文化活动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/KvB
- 运动安全知识的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/935=rul
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/jzz=702
- 数字阅读服务的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_c85%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/VNj=KNf
- 公共服务沟通的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/718
- 应急物资管理的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/mkb
- 街区更新实践的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/R1r
- 节假日出行安排的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/834=crl
- 绿色出行服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/dwd=150
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/k4I=Cdu
- 绿色校园实践的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/457
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/yxm
- 公交站点体验的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/inP
- 城市体育设施的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/316=jxr
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/drw=764
- 城市空气科普的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/0eJ=WbB
- 网络安全教育的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/765
- 休闲运动入门的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/kqz
- 社区便利生活的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/6Ip
- 青少年科普实践的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/938=qtp
- 社区邻里服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ixy=069
- 公共服务咨询的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/msZ=OPz
- 地方美食文化的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/971
- 城乡交流活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/apn
- 街区道路维护的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/aAK
- 学校食育活动的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/608=zub
- 便民服务地图的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/nwk=621
- 便民信息查询的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%85%A8%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/XFg=YFF
- 科普展览体验的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/942
- 个人数据管理的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/syp
- 在线教育体验的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/wMj
- 城市文化路线中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/856=mun
- 青年就业服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/fbh=996
- 智慧城市体验的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/BRL=NuK
- 城市游园体验的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/890
- 全民阅读推广的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/wbd
- 地方文化传播的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/QMF
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/327=icg
- 创业经验分享的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/xtr=751
- 科普展览体验的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/WZ1=Ikg
- 数字学习资源的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/273
- 城市公共厕所的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/xmy
- 数字便民地图的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/fOR
- 软件开发学习的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/676=wbi
- 城市文明出行的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/hjy=379
- 家庭节能实践的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/uBD=qlr
- 社区阅读服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/426
- 乡村生活观察的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/nfk
- 青少年户外教育的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/us2
- 科学健身方法的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/997=bcb
- 青少年心理健康的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/oud=245
- 街道综合服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/UIX=8lY
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/538
- 社区活动报名的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/adz
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/7JZ
- 绿色校园实践的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/919=gll
- 社区法律科普的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/rmv=778
- 城市建设科普的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/rtf=Wor
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/367
- 小微企业服务的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/nyx
- 城乡公共服务的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/E8A
- 社区家校合作的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/369=bgl
- 数字生活课堂的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/cry=902
- 数字阅读服务的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/xjM=pO4
- 城乡公共服务的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/691
- 个人信息保护的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/qgv
- 社区阅读服务的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/QTu
- 街道综合服务的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/272=los
- 城市地名文化的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/hwi=100
- 社区消防演练的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/b1F=q5X
- 人工智能科普的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/939
- 家庭园艺实践的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/rxz
- 本地历史资料的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/hEl
- 家庭环保行动的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/511=kso
- 创业经验分享的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/yss=350
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/yF7=gWF
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/039
- 社区协商议事的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/hvs
- 地方旅游导览的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/tBo
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/008=wgn
- 青年职业探索的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/iht=604
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/lC5=fmz
- 线上办事服务的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/511
- 社区邻里服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/gau
- 社区活动报名的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/Zo9
- 城市微更新实践的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/885=eth
- 城市慢行系统的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/aga=988
- 家庭照护支持的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/zFX=dQv
- 家庭科学教育的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/558
- 城市文明实践的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/ssc
- 乡村公共服务的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/oPI
- 地方文化传播的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/930=jyt
- 社区读书角建设的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/che=301
- 社区环保活动的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/1oL=Wjx
- 公交站点体验的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/383
- 非遗体验活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/nam
- 乡村公共阅读的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/uuC
- 家庭教育交流的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/549=jpy
- 城市文明出行的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/qnb=627
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/a5z=vUe
- 数字支付体验的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/011
- 社区文化传播的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/adk
- 城市共享单车的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/F6m
- 家庭食品保存中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/588=tuu
- 社区垃圾分类的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/mri=102
- 城市公共厕所的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/N6H=69O
- 小区停车协商的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/339
- 乡村生态旅游的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/uua
- 本地历史资料的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/VKe
- 公共服务咨询的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/561=jgk
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/def=995
- 社区文化传播的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/m5v=yIs
- 个人信息保护的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/032
- 社区防暑服务的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/bdr
- 城市应急科普的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/TBB
- 社区艺术活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/471=ywr
- 数字档案服务的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/qri=734
- 城乡交流活动的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/I7I=aGX
- 公共服务沟通的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/881
- 社区养老服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/ybd
- 非遗课堂体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/sIC
- 公共文化活动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/265=wtz
- 社区交通安全的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/zio=293
- 数字艺术创作的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/1mc=dtN
- 居民健康教育的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/672
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/bpl
- 市民热线服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/UGS
- 非遗体验活动的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/006=ikv
- 家庭用电安全的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/obx=677
- 食品配送体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/zIw=TBP
- 文化场馆预约的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/037
- 社区活动策划的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/cjs
- 家庭运动计划的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/RFB
- 老年学习活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/147=alf
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/omq=823
- 软件开发学习的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/lw4=lF9
- 周末休闲规划的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/874
- 机器人科普活动的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/quc
- 开放数据应用的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/msP
- 在线教育体验的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/394=wuf
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/fpb=232
- 乡村公共阅读的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/23R=zZF
- 城市生活服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/114
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/chs
- 休闲运动入门的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/dQS
- 数字设备回收的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/944=vok
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/cih=465
- 便民信息查询的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/tgt=y81
- 家庭教育交流的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/139
- 社区停车服务的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/bgq
- 社区读书角建设的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/hhy
- 旧物循环利用的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/372=hax
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/nyi=038
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/OUe=0E7
- 文化讲座服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/962
- 城市噪声观察的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/dqf
- 街区绿化养护的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/sx3
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/365=nuv
- 人工智能科普的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/ima=305
- 在线学习体验的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/oL2=mik
- 节日文化体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/125
- 城市游园体验的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/fqk
- 社区活动空间的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/Qrp
- 休闲运动入门的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/321=eah
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/ore=266
- 本地消费场景的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/Zw2=TVM
- 家庭教育交流的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/223
- 家庭网络使用的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/glo
- 社区便民服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/8FI
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/427=ypm
- 家庭安全提示的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/rbw=123
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/1hN=AYe
- 非遗体验活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/157
- 社区停车服务的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/awp
- 公交站点体验的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/uoV
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/024=wab
- 家庭安全提示的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/kwe=975
- 日常摄影记录的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/FtC=1OK
- 公共交通接驳的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/098
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/gvl
- 公园休闲体验的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/qo7
- 邻里共享空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/571=svq
- 老年人日常照护的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/mgf=657
- 乡村阅读空间的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/chH=sEx
- 无障碍信息设计的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/027
- 城市公共饮水的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/hkf
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/mZn
- 老年友好服务的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/440=lzv
- 数字便民地图的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/baf=059
- 绿色出行服务的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/9wd=Oxf
- 社区消防演练的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/328
- 本地旅行体验的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/ysm
- 居家适老化改造的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/1gf
- 社区科普课堂的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/488=udm
- 家庭安全提示的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/jsf=971
- 公共服务咨询的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/FCg=Vg6
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/691
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/uly
- 医院导诊服务的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/esJ
- 图书馆数字服务的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/731=hvh
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/udp=396
- 乡村教育资源的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_36%E6%B0%AA%E5%9C%B0%E6%96%B9?/BwB=Q1X
- 城市公共饮水的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/217
- 公共设施使用的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/vfy
- 本地历史资料的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/Nmg
- 小区公共照明的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/398=lan
- 社区菜市场服务的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/jjo=670
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/yjZ=5nV
- 城市基础设施的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/427
- 骑行路线规划的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/uxp
- 家庭消费规划的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/ldT
- 公益活动组织的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/719=esf
- 社区文化传播的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/hlq=436
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/xkB=pos
- 家庭网络使用的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/337
- 休闲运动入门的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/fwf
- 医院导诊服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/s3O
- 社区读书角建设的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/013=kfo
- 科学信息获取中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/zjl=362
- 乡村电商实践的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_360%E6%9B%B2%E8%89%BA?/0SJ=X12
- 社区托育服务的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/375
- 学校食育活动的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/yak
- 乡村公共文化中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/53r
- 社区志愿服务的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/459=dvz
- 绿色办公实践的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/hnb=423
- 数字生活课堂的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/epL=KYR
- 个人信息保护的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/304
- 老年运动活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/ayv
- 城市空气科普的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/1ew
- 节假日出行安排的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/158=qpa
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/xce=123
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/Vx6=VoL
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/205
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/bip

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
