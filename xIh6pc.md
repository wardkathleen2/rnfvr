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

- 社区快递服务的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/Leb
- 社区公共议事的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/130=zln
- 文化讲座服务的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/daw=666
- 家庭消费规划的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/DH3=wMH
- 食品安全科普的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/703
- 急救知识普及的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/orr
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/yy4
- 城市文明出行的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/331=scq
- 劳动教育实践的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/uir=970
- 社区艺术活动的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/qFb=oq2
- 青少年科技社团的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/849
- 社区故事采集的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/txp
- 图书借阅体验的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/Ghz
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/535=vgn
- 社区环保活动的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/mwf=715
- 公共空间导览的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/XH9=9ri
- 街区道路维护的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/801
- 科学信息获取的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/orj
- 社区互助网络的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/h6C
- 校园社团活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/346=src
- 便民信息查询的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/jce=442
- 社区活动报名的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/A0r=JI8
- 城市农夫市集的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/020
- 城市公共饮水的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/yuh
- 地方民俗记录的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/OvX
- 地方美食文化的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/137=vtq
- 文明养宠科普的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/zhr=200
- 个人时间管理的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/gmV=tyt
- 数字学习资源的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/187
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/ccb
- 小区公共照明的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/drC
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/696=znd
- 便民维修服务的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/avm=804
- 数字学习资源的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/sms=4tM
- 公共空间导览的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/866
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/zza
- 智慧停车服务的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/6Nj
- 乡村产业科普的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/452=rvm
- 开放数据应用的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vok=867
- 电子商务服务的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/od0=3ra
- 科学健身方法的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/788
- 社区安全巡查的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/lyz
- 生成式工具使用的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/yq8
- 安全出行教育的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/000=bxv
- 城市应急科普的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/akw=490
- 城市体育设施的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/qu1=XUw
- 城市步行友好的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/150
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/vty
- 公交无障碍服务的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/DwE
- 农村环境治理的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/020=nzt
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/tiq=407
- 校园阅读活动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/nX4=BAv
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/287
- 环境教育课程的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/aul
- 数字资源检索的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/Fgf
- 城市运动公园的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/539=nim
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/zda=424
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/CY4=aj7
- 城市便民驿站的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/033
- 老年智能设备的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/csi
- 数字公共文化的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/JLS
- 城市骑行环境的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/751=pwq
- 社区文化传播的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/onr=849
- 健康饮水科普的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/WN0=1OG
- 家庭理财科普的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/931
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/hhp
- 青年就业服务的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/f8e
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/517=zpl
- 创业经验分享的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/hwi=788
- 城市生活服务的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/dz9=Qje
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/528
- 社区家校合作的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/upa
- 智慧停车服务的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/b80
- 家庭安全提示的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/189=vuh
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/qwa=918
- 城市公共标识的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/bKM=GYQ
- 城市树木认养的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/699
- 社区手工活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/hal
- 社区快递服务的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/d5U
- 校园阅读活动的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/468=qaz
- 邻里共享空间的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/ikw=041
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/ReZ=9ng
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/061
- 课后服务体验的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/vbu
- 租房信息服务的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/cSO
- 城市微更新实践的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/470=xrs
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/xyh=529
- 小区公共照明的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/UHo=HgB
- 公共服务沟通的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/149
- 新能源出行的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/igy
- 城市公共标识的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/gfJ
- 社区心理支持的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/457=nwi
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/baj=001
- 城市公共厕所的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/yM5=UjR
- 社区协商议事的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/834
- 城市文明出行的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/nhx
- 城市应急广播的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/9Vh
- 公共服务指南的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/316=jlv
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/mpj=903
- 低碳社区实践的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/Rq7=rBb
- 社区便民服务的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/646
- 城市骑行环境的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/ycj
- 社区家校合作的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/7mg
- 社区养老服务的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/110=cjy
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/ozn=225
- 社区协商议事的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/t6i=WL2
- 家庭收纳实践的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/545
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/ewq
- 垃圾分类指导的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/0xd
- 家庭消费规划的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/483=yuq
- 社区老年食堂的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/lje=718
- 线上阅读资源的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BE%8E%E8%82%A1?/Jr7=BcI
- 文明养宠科普的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/902
- 地方文化传播的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/mql
- 全民健身活动的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/gQY
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/050=nqo
- 城市空气科普的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/wvt=101
- 远程协作工具的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/8Br=6vZ
- 基层医疗预约的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/866
- 文化讲座服务的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/twi
- 网络安全教育的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/uop
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/808=qwx
- 公共设施维护的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/wqr=292
- 社区文化传播的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/nb7=zmB
- 公共健身器材的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/551
- 家庭养老规划的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/avw
- 生活技能分享的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/IIU
- 社区活动报名的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/032=dfw
- 无障碍出行的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/kfh=625
- 城市文明出行的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/0o6=ZJ5
- 家庭安全提示的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/363
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/bnz
- 社区共享书架的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/SCU
- 周末休闲规划的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/465=svp
- 城市绿色交通的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/rrj=252
- 社区休闲设施的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/Wus=Fn5
- 线上办事服务的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/059
- 绿色校园实践的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/der
- 城市雨天出行的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/uHS
- 全民健身活动的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/510=xep
- 乡村生态旅游的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/kgo=964
- 社区活动报名中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/OMj=4n6
- 社区老年食堂的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/475
- 健康饮水科普中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/fhw
- 社区健康讲座中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/X1g
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/363=oyj
- 老年友好服务的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/irz=407
- 数字政务体验的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/R2E=XQW
- 本地旅行体验的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/010
- 城市文明实践的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/unt
- 软件开发学习的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/rQI
- 社区体育组织的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/756=aft
- 城市游园体验的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/ldi=233
- 绿色校园实践的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/LuY=iaK
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/042
- 绿色校园实践的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/uem
- 家庭理财科普的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/SFU
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/429=mbn
- 食品安全科普的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/ndc=971
- 社区心理支持的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/96I=yOG
- 智慧城市体验的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/330
- 社区交通安全的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/pfi
- 公共卫生设施的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/OzM
- 灵活就业交流的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/266=pyh
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/jin=533
- 口袋公园建设的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/nez=wrJ
- 青少年户外教育的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/404
- 社区便利生活的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/eaa
- 老年友好服务的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/mdk
- 新能源知识普及的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/467=usq
- 城市可持续生活的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/mux=999
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/GpY=4Id
- 乡村教育资源的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/200
- 公共场馆服务的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/uoi
- 城市公共艺术的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/mwa
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/492=pcp
- 青年职业探索的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/rxl=781
- 志愿服务平台的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/XW2=dXp
- 数字资源检索的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/521
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/xon
- 小区公共照明的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/1zV
- 公共交通信息服务的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/917=tlk
- 城市地名文化的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/wpd=894
- 租房信息服务的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/B1h=aDy
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/126
- 城市公共标识的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/kys
- 科学信息获取的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/v5e
- 网络安全教育的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/961=ggf
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/ong=035
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/mNR=7JD
- 家庭阅读计划的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/964
- 公共设施使用的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/zbp
- 药品使用科普的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/eMz
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/671=xhs
- 公共空间照明的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/asg=395
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/vn6=Psi
- 数字创意课程的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/516
- 便民服务地图的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/dqe
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/hE9
- 家庭安全提示的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/040=rnz
- 城市社区治理的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/xbl=325
- 老年数字阅读的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/FJv=CFL
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/464
- 数字地图应用的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/xjt
- 图书借阅体验的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/vh2
- 小区电梯维护的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/883=wzz
- 社区宠物管理的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/cmu=145
- 劳动教育实践的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/ae9=0jT
- 便民服务窗口的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/805
- 绿色出行服务的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/zlx
- 城市休闲步道的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/JRH
- 节约用水实践的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/816=snw
- 社区手工活动的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/bhw=460
- 老年智能设备的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/OlW=BRu
- 健康步道使用的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/198
- 城市地名文化的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/omi
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/9wk
- 个人信息保护的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/714=eas
- 环境监测科普的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/mas=070
- 乡村教育资源的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/424=gps
- 家庭环保行动的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/688
- 社区文化节活动的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/kzf
- 城市雨天出行的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/8dU
- 个人数据管理的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/565=pmr
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/hst=216
- 社区环保活动的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E5%9C%B0%E6%96%B9?/ycB=t5m
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/990
- 社区信息发布的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/vto
- 城乡交流活动的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/cjZ
- 家庭园艺实践的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/516=tub
- 城市树木认养的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/cwj=566
- 城乡公共服务的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E7%A8%8E%E5%8A%A1?/Kvq=DSN
- 城市博物馆活动的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/026
- 急救知识普及的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/sbl
- 青年就业服务的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/RuU
- 健康步道使用的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/540=mhd
- 社区艺术活动的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/jgu=533
- 网络信息辨识的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/B5z=g4B
- 社区交通安全的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/109
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/ovf
- 城市休闲步道的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/HLa
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/386=qgb
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/ypl=780
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/lEm=2tk
- 城市应急广播的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/266
- 公共服务预约的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/wsm
- 家庭节能设备的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/L23
- 青少年户外教育的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/409=lfc
- 儿童友好街区的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/oyd=446
- 居家防滑改造的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/rGi=jaJ

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
