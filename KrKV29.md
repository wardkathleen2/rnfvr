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

- 基层医疗预约的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/525
- 公共服务数字化的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/eux
- 家庭环保习惯的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/MAs
- 绿色快递包装的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/156=fgs
- 城市地名文化的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/yyi=010
- 城市文明实践的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%9A%E9%9B%85%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/dyX=4wh
- 生成式工具使用的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/897
- 口袋公园建设的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/dhj
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/5Ax
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/733=nat
- 农村环境治理的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/vqq=555
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%90%8F%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/tJS=PTY
- 城市适老服务的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/587
- 药品使用科普的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/gnm
- 居家适老化改造的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/OAD
- 家庭阅读计划的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/976=aja
- 社区交通安全的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/aoe=126
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%8F%AF%E9%9D%A0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/1oV=RLI
- 城市骑行环境的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/116
- 软件开发学习的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/bvd
- 儿童运动体验的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/pdB
- 城市地名文化的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/704=oaq
- 软件开发学习的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/puo=938
- 数据分析入门的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%90%8F%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%B1%9E%E4%BA%8E%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/hTb=wMk
- 读书会组织的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/524
- 基层服务创新的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/rgo
- 小区停车协商的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/vih
- 无障碍信息设计的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/815=tyi
- 社区应急准备的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/kkd=483
- 社区信息发布的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/1P7=Mgc
- 社区消防演练的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/971
- 城市公共自行车的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/psf
- 城市步行环境的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/GOF
- 灵活就业交流的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/526=ugv
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/pge=821
- 社区设施共享的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/XBZ=Zim
- 城市运动公园的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/825
- 城市体育设施的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/cad
- 街道综合服务的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/w8E
- 终身学习资源的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/944=qbs
- 城市微更新实践的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/alv=496
- 数字创意课程的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8F%AF%E9%9D%A0%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/V4K=Sdm
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/942
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/vki
- 节能生活方式的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/fJ3
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/153=rio
- 绿色生活实践的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/mdn=183
- 创业经验分享的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/VHv=smS
- 老年友好服务的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/018
- 生活垃圾回收的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/juo
- 城市住房服务的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/sOq
- 急救知识普及的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/351=whi
- 数字设备回收的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/dad=150
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/cGS=C0e
- 个人数据管理的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/243
- 社区花园共建的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/pvz
- 乡村生态观察的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/Ibu
- 青少年编程学习的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/911=uqt
- 街道综合服务的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/fwi=640
- 社区邻里服务的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/VqP=ykZ
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/614
- 绿色校园实践的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/xsn
- 公共服务评价中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/CHT
- 街区更新实践的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/561=lzc
- 在线学习体验的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/itk=842
- 城市文明出行的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/uvq=Ni8
- 老旧小区改造的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/465
- 城市步行友好中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/rel
- 社区体育组织的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/ihp
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/985=ato
- 城市住房服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/vau=568
- 无障碍出行的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/eab=iUX
- 社区绿色空间的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/878
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/ici
- 乡村文化空间的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/BAo
- 基层健康档案的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/003=gew
- 儿童阅读角的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/qqi=881
- 小区公共照明的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/1xE=Hyg
- 图书馆活动策划的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/297
- 物业服务沟通的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/tpj
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/e36
- 生活垃圾减量的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/005=vjs
- 数字生活课堂的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/wff=036
- 家庭用电安全的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E7%A8%B3%E5%AE%9A_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/LQn=dvm
- 老年智能设备的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/273
- 家庭环保行动的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/ojb
- 数字创意课程的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/aiY
- 公共卫生设施的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/106=ubv
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/zvt=861
- 社区文化节活动的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/g0U=6Ec
- 社区商业活力的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/144
- 数字地图应用的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/ccf
- 科学信息获取的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/KTO
- 便民服务窗口的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/248=cjy
- 青少年心理健康的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/bzr=145
- 节气饮食文化的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/QIr=6Zn
- 课后服务体验的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/839
- 在线学习体验的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/qdv
- 租房信息服务的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/xVQ
- 青少年科技社团的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/864=sti
- 家庭健康管理的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/cpo=967
- 城市便民驿站的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%BD%91%E6%8A%95%E7%BD%91%E5%9D%80_%E4%BF%A1%E8%88%86%E8%80%81%E5%8F%B0%E5%AD%90_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/tGU=lxX
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/222
- 个人数据管理的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/zdk
- 绿色生活实践的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/zcP
- 社区文化节活动的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/210=fvi
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/hoh=884
- 职业技能学习的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%BD%91%E6%8A%95ag_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/8uT=O1Z
- 灵活就业交流的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/344
- 户外活动组织的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/ktg
- 家庭健康科普的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/YHX
- 城市雨天出行的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/112=xjo
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/fsj=117
- 数字艺术创作的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/xxE=Rrn
- 消防知识宣传的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/662
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/wlo
- 亲子阅读活动的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/RCo
- 网络安全教育的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/863=vja
- 社区绿色空间的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/jbg=836
- 公共设施使用的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/fU9=qt7
- 家庭食品保存的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/149
- 便民服务地图的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/xmv
- 数字政务体验的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/eLa
- 数据分析入门的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/645=lbj
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/pla=053
- 数字公共文化的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/MfI=rmS
- 社区科普课堂的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/455
- 数字公共文化的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/xvm
- 科技馆参观体验的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/1ZY
- 医院导诊服务的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/116=qqn
- 消防知识宣传的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/sgc=721
- 地方民俗记录的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/rVy=SJ1
- 城市可持续生活的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/543
- 儿童友好街区的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/vae
- 智能家居应用的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/nRd
- 环境教育课程的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/627=fmy
- 家庭科学教育的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/qjo=976
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/ZbU=0Je
- 社区学习活动的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/590
- 便民信息查询的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/khd
- 青少年科技社团的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/VS0
- 农贸市场环境的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/397=sqe
- 城市博物馆服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/uqk=048
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/PTv=gYX
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/376
- 儿童户外活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/aou
- 无障碍出行的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/p3Y
- 街区道路维护的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/130=vyk
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/srm=978
- 社区信息发布的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/FAI=yqh
- 社区活动空间的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/205
- 户外活动组织的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/esb
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/gr1
- 网络信息辨识的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/288=yzp
- 儿童友好街区的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/qaf=934
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/Iyx=bQi
- 数字艺术创作的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/586
- 家庭用电安全的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/zti
- 社区养老服务的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/IEH
- 学校食育活动的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/571=iku
- 家庭用电安全的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/sek=886
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/53V=z9Z
- 城市骑行环境的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/668
- 社区家校合作的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/hcq
- 公共图书馆服务的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/31X
- 医院导诊服务的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/179=usy
- 数字艺术创作的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/zav=947
- 智能手机助老的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/mhc=NQa
- 城市慢行系统的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/321
- 城市文化路线的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/dxt
- 周末休闲规划的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/wjz
- 街头绿植养护的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/649=iru
- 地方文化传播的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/ran=538
- 本地旅行体验的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/wcJ=ol6
- 校园安全教育的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/443
- 数字地图应用的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/yxy
- 乡村公共服务的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/6Te
- 城乡交流活动的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/126=kcd
- 城市绿道建设的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/bjx=831
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/KBO=3yP
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/955
- 社区老年食堂的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/gag
- 新能源出行的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/N9k
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/666=aal
- 医院导诊服务的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/hsn=764
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_360?/wCG=P6o
- 城市便民驿站的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/859
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/aaa
- 儿童运动体验的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/3iv
- 社区便利生活的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/858=yjg
- 新能源出行的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/cwa=824
- 终身学习资源的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/rr1=EEU
- 便民服务地图的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/370
- 城市运动公园的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/gta
- 健康步道使用的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/euH
- 机器人科普活动的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/425=jbw
- 健康饮食教育的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/wjc=520
- 城市慢行系统的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E6%BE%8E%E6%B9%83?/Owm=hFw
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/007
- 非遗体验活动的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/imy
- 老年人文化生活的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/mDn
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/997=ajt
- 社区花园共建的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/svj=762
- 社区科普课堂的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/VAn=EGT
- 学校食育活动的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/286
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/eon
- 家庭网络使用的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/Tq4
- 消防知识宣传的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/593=akf
- 社区慢性病防控的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/msr=686
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/Wxs=Hh9
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/897
- 便民维修服务的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/xgb
- 老年人日常照护的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/Yn7
- 公共卫生宣传的服务体验观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/241=hbj
- 旧物循环利用的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/pbl=831
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/hWw=2lU
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/185
- 街区更新实践中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/phx
- 课后服务体验的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/bQi
- 城市休闲步道的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/248=wzl
- 城市社区治理的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/bsc=968
- 口袋公园建设的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/a53=74E
- 乡村生态观察的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/425
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/lby
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/jQd
- 社区家政服务的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/173=hrw
- 家庭科学教育的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/nlw=851
- 图书借阅体验的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/jWG=ccD
- 节气饮食文化的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/588
- 食品配送体验的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/uop
- 周末休闲规划的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/2AH
- 城市住房服务的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/902=qvz
- 社区心理支持的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/ipt=966
- 便民信息查询的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/7Bz=OjY
- 全民健身活动的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/489
- 科学运动指导的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/mub
- 数字学习资源的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/L1V
- 课后服务体验的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/625=iun
- 基层健康服务的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/mdy=921
- 周末休闲规划的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/F1m=Pog
- 新能源出行的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/655
- 通勤路线规划的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/cuv
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/09w
- 家庭用电安全的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/146=cwc
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/bdp=116
- 科学观察活动的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/glI=N5O
- 公园亲子设施中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/057
- 公共服务评价的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/mif
- 城市绿色交通的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/TuT
- 乡村公共服务的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/038=dtj

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
