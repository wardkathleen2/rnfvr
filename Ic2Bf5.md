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

- 终身学习资源的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/nab=256
- 开源技术交流的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/5Co=eqP
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/553
- 家庭节能实践的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/abd
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/RHi
- 健康信息获取的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/054=lqr
- 科普展览体验的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/fsd=652
- 街区道路维护的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/TWe=dK8
- 绿色出行服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/454
- 公园亲子设施中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/utk
- 城市农夫市集的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/VzZ
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/557=cel
- 数字艺术创作的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/cnx=367
- 城市公共自行车的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/kj8=sQv
- 家庭节能实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/845
- 邻里共享空间的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/cee
- 社区科普课堂的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/6aF
- 街区小店体验的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/263=fdn
- 社区活动空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/hug=880
- 学校体育活动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/SoD=3uE
- 家庭理财科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/392
- 社区修缮行动的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/nfv
- 数字阅读服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/jWS
- 城乡公共服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/315=amz
- 软件开发学习的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/cpf=190
- 城市应急广播的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%85%AC%E5%91%8A?/XVY=o2R
- 城市生活记录的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/718
- 家庭阅读计划的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/ogd
- 无障碍出行的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/eC5
- 城市适老服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/652=heh
- 社区儿童活动的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/rjc=133
- 户外活动组织中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/fqN=YLT
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/867
- 城市文明实践的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/fkd
- 社区科普课堂的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/z81
- 公共设施维护的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/831=pls
- 儿童安全出行的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/zjs=983
- 老年运动活动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/k7A=3zn
- 社区科普课堂的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/148
- 乡村文化空间的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/ori
- 环境教育课程的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/9tB
- 户外活动组织的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/063=ath
- 城乡交流活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/eao=276
- 科普展览体验的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/mGa=5wu
- 家庭节能实践的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/019
- 物业服务沟通的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/cxx
- 城市适老服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/Gaz
- 社区便民服务的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/134=rvu
- 儿童友好空间的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/nxf=012
- 数字课堂应用的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/omE=noG
- 家庭阅读计划的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/904
- 社区体育组织的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/lwc
- 绿色生活实践的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/4Ff
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/480=htn
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/adw=273
- 老年智能设备的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/gtI=AuX
- 公共服务咨询的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/534
- 小微企业服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/xna
- 小区公共照明的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/B3Z
- 城市微更新实践的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/630=qqj
- 家庭安全提示的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/fvy=008
- 科学健身方法中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9?/6xP=SkJ
- 垃圾分类指导的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/307
- 数字公共文化的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/rbc
- 安全出行教育的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/cHT
- 灵活就业交流的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/193=qvk
- 数字创作工具的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/xrj=778
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/w7q=Fqy
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/398
- 社区修缮行动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/qmg
- 乡村生态旅游的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/fFw
- 节假日出行安排的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/357=xcl
- 志愿服务平台的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/yzd=044
- 绿色建筑理念的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/XzW=Fnd
- 绿色生活实践中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/635
- 社区公共议事的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/bip
- 家庭食品保存的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/QJN
- 街道综合服务的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/432=sno
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/xwi=666
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%85%A7%E7%9C%BC?/Qrm=zjq
- 公共设施维护的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/227
- 街头绿植养护的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/npv
- 街区小店体验的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/Nfx
- 公交站点体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/638=rzl
- 社区邻里服务的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/eug=545
- 城市慢跑路线的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/dvk=CeH
- 街头绿植养护的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/658
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/goe
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/tCF
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/522=ozp
- 城市生活记录的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/lgs=959
- 安全出行教育的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/RZw=drp
- 地方旅游导览的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/377
- 科学教育活动的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/qza
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/guG
- 城市噪声观察的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/438=vum
- 在线教育体验的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/pop=163
- 社区科普课堂的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_360%E6%B3%95%E6%B2%BB?/bOR=7w9
- 生活服务数字化的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/646
- 社区儿童活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/fed
- 基层服务创新的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/8hm
- 市民意见收集的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/804=rxe
- 乡村文化空间的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/cdo=259
- 社会体育指导的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/vq6=sxn
- 农业科普体验的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/967
- 节能生活方式的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/fxq
- 科普展览体验的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/Ymg
- 老年运动活动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/314=kqb
- 乡村公共文化的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/zel=074
- 老年友好服务的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90?/xWP=C4t
- 开放式学习空间的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/075
- 城乡公共服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/kcs
- 电子商务服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/e59
- 青年志愿活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/694=zcm
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/khu=530
- 城市休闲步道的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/hoz=0ma
- 公共卫生宣传的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/262
- 节约用水实践的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/kxx
- 数字支付体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/Q3T
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/377=exw
- 租房信息服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/elu=576
- 儿童户外活动的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/2tL=yPQ
- 乡村生态观察的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/649
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/qdi
- 居家适老化改造的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/eDH
- 电子商务服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/609=okg
- 在线教育体验的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/ykf=623
- 城市慢跑路线的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/sZk=lhm
- 公共服务数字化的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/740
- 环境教育课程的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/efp
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/xUv
- 社区读书角建设的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/057=bee
- 城市公共空间的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/ahw=056
- 文化场馆预约的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/aCn=LiX
- 小区电梯维护的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/538
- 个人信息保护的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/ofz
- 市民意见收集的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/jN6
- 家庭健康科普的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/097=diq
- 社区商业活力的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/esr=786
- 家庭科学教育的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/rYK=oqj
- 城市夜间照明的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/997
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/ryb
- 公共空间休憩的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/Ue6
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/307=iqq
- 城市应急科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/pis=295
- 城市可持续生活的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/ns2=2l9
- 无障碍信息设计的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/754
- 节能生活方式的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/htl
- 社区体育组织的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/z4m
- 旧物循环利用的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/825=yog
- 数字设备回收的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/nqt=549
- 全民阅读推广的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/Nc9=zNI
- 地方民俗记录的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/944
- 城市农夫市集的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/xeh
- 智能家居应用的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/pSe
- 节能家电使用的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/945=mrh
- 社区家校合作的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/eof=570
- 家庭科学教育的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/o2f=Fg0
- 线上阅读资源的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/302
- 生成式工具使用的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/ndr
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/MrK
- 生活垃圾回收的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/457=dly
- 医院导诊服务的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/exa=892
- 老年人日常照护的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/nJ2=0g4
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/171
- 软件开发学习的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/hfw
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/xx5
- 口袋公园建设的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/206=wwf
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/dpo=169
- 节能家电使用的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/VKa=uX1
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/189
- 绿色消费选择的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/paj
- 线上阅读资源的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/uFn
- 人工智能科普的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/679=zai
- 数字支付体验的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/kkf=756
- 校园社团活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/yUt=vkq
- 科技馆参观体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/328
- 社区公共卫生的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/rjn
- 城市公共饮水的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/XKX
- 家庭健康科普的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/509=uwy
- 城市住房服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/tgm=608
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/NJE=xpr
- 职业技能学习的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/997
- 邻里共享空间的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/qek
- 光伏知识科普的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/a9K
- 城市噪声观察的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/860=ggt
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/wmz=003
- 城市水环境观察的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E5%BF%85%E5%BA%94%E6%88%BF%E4%BA%A7?/gHP=t1J
- 公共服务沟通的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/301
- 科学健身方法的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/bis
- 家庭用电安全的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/Jl9
- 公共空间照明的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/196=vza
- 乡村生态观察的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/jcz=497
- 基层医疗预约的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/tfv=xOo
- 乡村产业科普的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/518
- 社区科普课堂的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/ezu
- 非遗体验活动的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/4Hh
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/621=awq
- 居家防滑改造的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/fgk=573
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/9JP=Mql
- 城市展览体验的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/833
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/utd
- 社区商业活力的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/wh8
- 社区体育组织的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/543=bvj
- 文化讲座服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/dyg=964
- 社区绿色空间的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/iGd=WDM
- 街道综合服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/471
- 社区共享书架的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/itx
- 城市骑行环境中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/WJF
- 科普展览体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/073=oyp
- 老年数字阅读的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/usi=093
- 家庭志愿活动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/gVu=eZD
- 生活垃圾减量的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/969
- 城市公共标识的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/odb
- 乡村文化活动的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/i0Y
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/664=vuc
- 公共空间导览的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/pgw=918
- 节假日出行安排的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/T8x=wek
- 健康饮食教育的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/631
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/rvw
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/uHG
- 居家防滑改造的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/288=edl
- 数字创作工具的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/epp=172
- 软件开发学习的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/FS8=5gW
- 学校食育活动的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/026
- 校园社团活动的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/rgq
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/0Dx
- 绿色办公实践的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/531=wdy
- 小微企业服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/gwh=710
- 社区体育组织的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/Tir=ZXO
- 城市生活记录的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/074
- 社区文化节活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/icd
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/HyB
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/119=spg
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/bcy=874
- 乡村生态观察的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/p68=YAp
- 公共服务预约的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/282
- 科学运动指导的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/qan
- 在线学习体验的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/pQa
- 本地消费场景的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/858=gfa
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/mob=756
- 家庭节能实践的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/bfZ=hed
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/160
- 公共卫生设施中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/nau
- 小区停车协商的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/i4J
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/386=qdm
- 休闲运动入门的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/gqc=393
- 社区消防演练的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/60E=0zX
- 智能手机助老的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/745
- 文化场馆预约的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/lvk

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
