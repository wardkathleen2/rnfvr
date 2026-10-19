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

- 城市休闲步道的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/lch
- 社区休闲设施的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/922=nka
- 公共服务预约的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/ktf=791
- 城市文明实践的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/dpk=hHw
- 远程协作工具的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/324
- 社区法律科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/tjy
- 地方旅游导览的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/Tot
- 节能家电使用的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/497=ecs
- 社区养老服务的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/mre=366
- 租房信息服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/Avi=U54
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/007
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/gxi
- 本地旅行体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/oHa
- 网络信息辨识的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/485=kzt
- 科学教育活动的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/ase=284
- 节假日出行安排的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/u1z=pDS
- 社区庭院绿化的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/180
- 消防知识宣传的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/fnr
- 绿色办公实践的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/6M6
- 骑行路线规划的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/333=mkl
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/ucz=673
- 家庭用电安全的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%97_360%E6%AF%8D%E5%A9%B4?/yIz=1QJ
- 城市公共饮水的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/790
- 城市绿色交通的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/sww
- 个人信息保护的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/GP4
- 家庭健康管理的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/200=nvy
- 儿童安全出行的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/buh=361
- 城市可持续生活的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E7%89%88.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500top_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/Gmx=LOd
- 环境教育课程的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/745
- 环境教育课程的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/vth
- 城市博物馆活动的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/V4d
- 城市公共厕所的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/808=qcl
- 物业服务沟通的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/vpw=062
- 非遗体验活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%85%9A%E5%BB%BA?/4GW=aDc
- 公共空间照明中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/715
- 节能生活方式的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/uyy
- 社区活动空间的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/DBX
- 城市公共空间的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/943=blw
- 科学信息获取的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/uwm=065
- 应急物资管理的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%B0%81_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/YWJ=Z4D
- 食品安全科普的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/973
- 社区生活指南的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/hgb
- 急救知识普及的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/Xxi
- 青年志愿活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/430=ukd
- 乡村生态旅游的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/hec=994
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E7%AB%AF%E4%BA%86%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/J4k=a6o
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/471
- 文明养宠科普的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/adg
- 个人数据管理的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/8r1
- 社区健康讲座的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/545=cds
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/rxc=956
- 城市基础设施的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E3d%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/Xav=0ms
- 公共文化活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/400
- 环境教育课程的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/asq
- 社区便民集市的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/8Jp
- 社区宠物管理的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/799=ksj
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/dtt=532
- 乡村公共服务的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E9%80%9A%E5%85%B3%E6%B3%A8%E5%8F%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/57X=u3n
- 本地旅行体验的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/337
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/eok
- 科学信息获取的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/hpV
- 乡村文化活动的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/868=peu
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/rke=627
- 城乡公共服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8VI_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/qdy=Uhp
- 公共设施维护的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/513
- 城市骑行环境的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/abx
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/5Um
- 城市共享单车的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/762=feb
- 家庭安全提示中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/kxt=172
- 社区公共卫生的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E3d%E6%A8%A1%E6%8B%9F%E8%AF%95%E6%9C%BA%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/WQn=dHl
- 城市运动公园的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/740
- 基层健康档案的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/elc
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/neJ
- 科学教育活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/349=ixi
- 居民健康教育的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/oog=901
- 城市运动公园的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%A6%8F%E5%BD%A93d%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9?/kjN=a8z
- 城市骑行环境的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/483
- 社区邻里服务的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/alq
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/Elt
- 社区环保活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/957=mpe
- 网络信息辨识的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/brl=014
- 城市步行环境的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E9%80%9A%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/nYu=o6F
- 乡村公共服务的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/484
- 读书会组织的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/gyx
- 社区邻里服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/yoD
- 社区共享书架的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/847=jjb
- 地方戏曲体验的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/ymr=868
- 城市骑行环境的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/uCV=5jj
- 安全出行教育的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/662
- 乡村阅读空间的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/zmb
- 社区绿色空间的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/AfG
- 家庭环保习惯的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/352=mhv
- 节能家电使用的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/qkj=883
- 社区便民集市的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/Qqd=YCg
- 节能生活方式的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/392
- 科学教育活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/mnk
- 公共图书馆服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/JcE
- 城市休闲步道的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/176=mzn
- 社区故事采集的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/tcd=845
- 图书馆数字服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/D9F=Gfk
- 职业技能学习的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/927
- 科学运动指导的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/aen
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/IUf
- 儿童友好空间的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/368=oiw
- 社区修缮行动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/rtk=495
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/Lwi=tp1
- 公共文化活动的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/576
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/guh
- 社区便利生活的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/csI
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/454=bsw
- 社区消防演练的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/rsg=847
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/hpN=Nyn
- 青少年户外教育的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/162
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/eri
- 开源技术交流的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/Glc
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/868=bqv
- 公园无障碍服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/yph=820
- 城乡交流活动的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8v%C4%B1lll_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/8GH=h1Y
- 绿色出行服务的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/441
- 社区手工活动的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/sxj
- 乡村电商实践的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/KXI
- 数字支付体验的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/505=jhu
- 读书会组织的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/sli=687
- 家庭节能设备的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%A3%9F%E5%93%81?/iLs=03A
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/310
- 消防知识宣传的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/xdn
- 乡村生态观察的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/ubd
- 科学运动指导的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/000=ruf
- 数字阅读服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/nso=878
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/xwE=6t7
- 公交站点体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/675
- 家庭环保习惯的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ele
- 儿童阅读角的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/jBn
- 全民阅读推广的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/022=npc
- 青少年户外教育的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/zqh=349
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/SlR=7yp
- 青少年科技社团的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/224
- 公共空间导览中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/yuj
- 家庭安全提示的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/oKN
- 科学健身方法的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/219=fnb
- 开放数据应用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/ebg=764
- 通勤路线规划的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/mQe=9P7
- 图书馆活动策划的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/900
- 城市噪声观察的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/exi
- 食品配送体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/p61
- 小区公共照明的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/317=neh
- 老年人文化生活的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/qhv=888
- 社会体育指导的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/ohv=Dwd
- 社区安全巡查的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/717
- 城市公共艺术的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/odt
- 图书借阅体验的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/vqK
- 城市应急科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/126=vhv
- 社区庭院绿化的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/szb=967
- 小区停车协商的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/VNy=VwC
- 社区托育服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/516
- 城市生活记录的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gfa
- 数字艺术创作的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yUo
- 网络信息辨识的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/690=uqd
- 生活服务数字化的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eyy=754
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mro=XDd
- 社区艺术活动的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/966
- 新能源知识普及的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/geo
- 校园阅读活动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/DFd
- 社区宠物管理的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/412=qxh
- 生活服务数字化的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/fxi=189
- 城市噪声观察的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/pJa=qHD
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/735
- 安全出行教育的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/afo
- 家庭饮食安排的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/cC0
- 租房信息服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/998=sdv
- 在线学习体验的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/akm=230
- 社区商业活力的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%B9%A6%E7%94%BB?/w42=p2x
- 光伏知识科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/324
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/fzg
- 社区活动空间的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/fqX
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/857=kkz
- 社区防暑服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/cmj=129
- 公共服务指南的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/ZBK=Nhx
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/941
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/jle
- 环境教育课程的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/drD
- 家庭健康管理的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/942=wgk
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/iqc=190
- 远程协作工具的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/Nze=X6I
- 数字地图应用的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/488
- 电子商务服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/gog
- 社区便民服务的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/wlG
- 乡村生态观察的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/709=tod
- 便民服务窗口的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/lif=917
- 城乡交通衔接的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8767%E5%92%95%E5%92%95%E7%8C%AA%E7%89%88_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/pi1=S6O
- 志愿者培训交流的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/794
- 社区体育组织的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/ddl
- 节气饮食文化的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/XxS
- 公共交通接驳的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/891=xlz
- 职业技能学习中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/bcu=618
- 应急物资管理的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E9%87%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/bcR=QLf
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/138
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/tsc
- 儿童安全出行的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/Ylf
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/003=qvr
- 全民健身活动的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/uhi=803
- 家庭健康科普的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E5%AE%A2%E6%9C%8D_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/p95=wha
- 城市雨天出行的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/778
- 校园阅读活动的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/get
- 学校食育活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/6BH
- 城市生活记录的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/862=hly
- 数字设备回收的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/iva=646
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/W39=IU4
- 便民服务窗口的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/411
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/ozt
- 终身学习资源的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/GEN
- 城市绿色交通的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/108=pfv
- 乡村文化空间的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/cqj=810
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/X9A=1P0
- 城市公共艺术的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/299
- 城市地名文化的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/iui
- 家庭照护支持的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/I7b
- 公共空间导览的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/698=qtn
- 科学信息获取的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/gqt=145
- 社区绿色空间的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/yj7=FB3
- 软件开发学习中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/864
- 科学观察活动的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/fvd
- 儿童友好空间的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/byS
- 社区防暑服务的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/007=krh
- 网络安全教育的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/aes=891
- 社区活动报名的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/qEu=O8z
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/638
- 农产品消费体验的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/fzm
- 户外活动组织的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/i8Z
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/564=jrf
- 无障碍信息设计的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/xno=623
- 青年职业探索的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/SQb=H1J
- 数字政务体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/302
- 新能源出行的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/zvp
- 职业技能学习的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/6N4
- 乡村公共服务的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/895=omb
- 健康饮水科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/xih=006
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/Yt0=4jK
- 急救知识普及中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/109
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/hqc
- 无障碍信息设计的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/7iv
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/822=phb
- 城市步行友好的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/bvv=993
- 城市步行环境的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%B9%90%E5%BD%A9%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_360%E5%88%9B%E6%8A%95?/vGq=IoW
- 亲子科普活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/589
- 乡村公共阅读的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/moq
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/bAn
- 科学观察活动的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/282=czx
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/enz=390
- 周末休闲规划的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%B9%90%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/Tma=mBR

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
