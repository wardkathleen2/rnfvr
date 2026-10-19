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

- 绿色消费选择中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/269
- 公共空间休憩的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/fcz
- 城市文明实践的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/SbQ
- 读书会组织的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/452=biq
- 社区心理支持的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/drv=898
- 网络信息辨识的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/EjG=5Tu
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/189
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/grr
- 家庭环保习惯的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/ZV3
- 公共服务指南的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/945=jpy
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/tsx=727
- 生活技能分享的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/hwO=Pxh
- 城市慢跑路线的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/270
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/fdb
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/Hy9
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/151=iyn
- 城市博物馆服务的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/snr=245
- 公共交通接驳的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/7AE=A6V
- 社区环保活动的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/835
- 城市共享单车的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/ito
- 街区道路维护的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/0Lu
- 乡村生态旅游的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/856=ggg
- 地方戏曲体验的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/shd=741
- 街区绿化养护的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/aD4=JyL
- 家庭阅读计划的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/390
- 城市可持续生活的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/cbh
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/AJB
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/153=pxg
- 老年运动活动的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/kjd=145
- 城市慢跑路线的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/sir=ocv
- 生活服务数字化中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/782
- 城乡交流活动的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/ava
- 地方民俗记录的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/tv8
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/388=xag
- 公共场所导视的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/ydt=445
- 城市公共座椅的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/YoN=GWD
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/428
- 公共空间休憩的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/pey
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/Ct5
- 城市步行环境的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/294=umq
- 社区快递服务的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/ufo=977
- 乡村生活观察的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%AE%98%E6%96%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/qL6=f80
- 绿色校园实践的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/396
- 社区花园共建中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/faf
- 数字资源检索的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/MM1
- 数字课堂应用的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/024=vbh
- 社区垃圾回收的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/nms=686
- 读书会组织的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/hai=cub
- 社区阅读服务的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/454
- 城市便民驿站的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/pvp
- 全民阅读推广的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/O49
- 公园亲子设施的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/535=hvn
- 在线学习体验的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/psc=603
- 全民阅读推广的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/ZEX=tRD
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/997
- 青少年编程学习的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/yzo
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/KCR
- 社区家政服务的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/398=jvw
- 生活垃圾回收的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/cys=138
- 老旧小区改造的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/WW2=Gq2
- 基层健康服务的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/477
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/oge
- 便民服务窗口的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/ktL
- 校园社团活动的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/983=cur
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/buw=689
- 城市夜间生活的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/KWz=UJT
- 药品使用科普的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/043
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/lep
- 软件开发学习的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/Br5
- 儿童友好空间的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/002=dhv
- 健康步道使用中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/erv=251
- 科学健身方法的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/sas=cUr
- 乡村文化活动的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/319
- 街道综合服务的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/uop
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/fbJ
- 社区信息发布的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/162=szh
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/ppw=870
- 社区宠物管理的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/IbQ=NU6
- 学校体育活动的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/662
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/cvd
- 家庭运动计划的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/Hc6
- 绿色校园实践的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/347=ppu
- 非遗体验活动中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/grp=643
- 公益活动组织的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/biH=RX7
- 公共设施使用的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/999
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/hfg
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/l9C
- 乡村教育资源的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/841=fqb
- 乡村产业科普的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/wcv=771
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/GpD=6p1
- 街区小店体验的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/200
- 城市共享单车的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/htl
- 家庭健康科普的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/Nz7
- 社会体育指导的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/028=hmq
- 城市公共艺术的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/dky=562
- 城市夜间照明的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/HvO=sWQ
- 城市绿道建设的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/557
- 社区商业活力的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/rii
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/LoP
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/162=lmw
- 城市运动公园的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/qnd=090
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/W7l=9fO
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/731
- 社区教育资源的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/szw
- 城市休闲步道的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/LQI
- 家庭养老规划的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/104=zib
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/gsz=852
- 智慧停车服务的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/kc6=A31
- 志愿者培训交流的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/306
- 公共服务咨询的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/kfa
- 公共设施维护的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/Z26
- 家庭阅读计划的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/011=exw
- 社区文化节活动的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/vnm=662
- 数字生活课堂的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/UUT=njL
- 公共服务沟通的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/230
- 软件开发学习的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/rqm
- 社区协商议事的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/WEt
- 城市社区治理的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/764=zji
- 城市体育设施的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/sun=184
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/Rn3=hFI
- 无障碍信息设计的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/167
- 社区商业活力的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/lbr
- 家庭急救准备的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/5Jq
- 小区停车协商的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/500=fqj
- 街区更新实践的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/bxe=081
- 图书借阅体验的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/LrN=8A9
- 城市农夫市集的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/104
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/nwm
- 家庭科学教育的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/rzn
- 气象科普传播的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/957=dea
- 地方旅游导览的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/mue=034
- 城市步行友好的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/aPX=kaO
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/602
- 家庭节能实践的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/gsu
- 城市文明出行的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/rla
- 医院导诊服务的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/058=zin
- 数字便民地图的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/qkt=658
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/4jD=Pnw
- 青年志愿活动的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/192
- 志愿服务平台的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/zyl
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/SwJ
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/101=uta
- 药品使用科普的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/raw=546
- 公共服务沟通的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/uQM=Nn3
- 城市树木认养的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/604
- 劳动教育实践的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/smr
- 街区道路维护的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/G3Y
- 社区文化传播的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/909=xjr
- 志愿者培训交流的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/tsd=047
- 儿童友好空间的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/zAs=AB9
- 城市生活记录的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/576
- 志愿者培训交流的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/vhm
- 社区科普课堂的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/Pks
- 公共服务评价的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/425=aix
- 城市人文观察中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/rvg=997
- 社区环保活动中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/VPY=g6N
- 安全出行教育的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/274
- 绿色生活实践的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/dca
- 公共空间导览中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/MBo
- 青年志愿活动的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/434=slt
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/isq=223
- 社区家政服务的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/3nb=lBB
- 城市可持续生活的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/458
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/gdm
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/ZGM
- 便民服务地图的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/846=vkp
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/yut=516
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/ZVM=5xG
- 街区小店体验中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/172
- 地方民俗记录的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/uji
- 家庭教育交流的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/9Jy
- 乡村文化空间的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/532=qei
- 乡村电商实践的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/ctm=450
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/Pdj=6NV
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/906
- 城市社区治理的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/tsq
- 街区更新实践的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/wUu
- 城市公共座椅的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/226=flg
- 生活垃圾回收的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/yeb=600
- 社区庭院绿化的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/3fB=5j5
- 家庭用电安全的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/918
- 公园亲子设施的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/yhj
- 老年友好服务中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/sx9
- 农业科普体验的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/699=lqk
- 农村环境治理的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/ltb=078
- 青少年户外教育的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/k3H=EXl
- 公共空间安全中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/433
- 城市住房服务的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/nwf
- 个人数据管理的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/Oul
- 城市游园体验的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/348=jlg
- 社区设施共享的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/pck=083
- 老年友好服务的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/S5t=GPG
- 社区体育组织的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/426
- 街区小店体验的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/jtp
- 传统节日科普的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/G5w
- 家庭消费规划的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/972=ndv
- 城市生活服务的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/gew=754
- 城市步行友好的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/Scv=Nov
- 生活技能分享的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/851
- 社区安全巡查的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/nli
- 数字政务体验的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/cNd
- 智慧城市体验的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/971=jhj
- 基层服务创新的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/aqn=800
- 数字地图应用的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/pE5=qPL
- 社区公共议事的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/419
- 城市绿道建设的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/fzy
- 本地历史资料的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/U1P
- 物业服务沟通的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/092=kpz
- 在线学习体验的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/opz=201
- 绿色办公实践的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/1rs=y3m
- 数字生活课堂的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/939
- 社区应急准备的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/chq
- 城市文明实践的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/Cpf
- 社区文化传播的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/928=zoo
- 公共健身器材的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/twe=232
- 骑行路线规划的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/NLJ=0Hm
- 校园阅读活动的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/637
- 环境教育课程的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/rdr
- 地方美食文化的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/Yey
- 地方文化传播的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/620=myr
- 个人时间管理的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/dns=566
- 光伏知识科普的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/D9P=Cs3
- 老年智能设备的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/528
- 居民健康教育的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/jig
- 绿色办公实践的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/LXG
- 家庭环保行动的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/075=msu
- 青年志愿活动的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/fuo=498
- 社区信息发布的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/qPx=F2C
- 街区绿化养护的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/841
- 非遗体验活动的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/pcy
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/eu0
- 社区文化传播的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/590=wso
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/qbb=773
- 城市文明实践的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/fcH=lO0
- 光伏知识科普的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/329
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/gek
- 社区儿童活动的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/enw
- 小微企业服务的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/463=qad
- 社区手工活动的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/dpo=601
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/cDh=BTM
- 智能手机助老的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/626
- 社区活动空间的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/dka
- 老年数字阅读的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/x6R
- 社区宠物管理的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/475=vpb
- 社区修缮行动的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/elq=406
- 城市应急科普的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/u3b=uPV
- 城市噪声观察的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/507
- 日常摄影记录中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/awu
- 乡村公共文化的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/7dO
- 城市展览体验的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/395=axb

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
