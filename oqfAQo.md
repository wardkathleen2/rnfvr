# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:23**

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

- 就业技能培训的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/okj=487
- 城市体育设施中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/KE8=LjY
- 创业经验分享的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/348
- 儿童阅读角中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/agc
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/6rc
- 公共设施使用的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/904=meq
- 图书借阅体验的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/ybg=311
- 公共服务数字化的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/YEH=Oi2
- 数据分析入门的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/127
- 街区道路维护的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/eru
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/cQm
- 数字素养提升的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/383=lcx
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/nro=870
- 社区共享书架中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/6qD=ikD
- 社区便民集市的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/452
- 乡村教育资源的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/cid
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/XRY
- 社区家政服务的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/671=uox
- 社区活动策划的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/ajc=252
- 旧物循环利用的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/Npj=TLI
- 公交无障碍服务的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/523
- 科学运动指导的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/aid
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/JFs
- 老年人文化生活的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/313=sux
- 远程协作工具的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/erv=031
- 安全出行教育的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0fh20-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/gh9=IxY
- 家庭健康科普的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/858
- 社区心理支持的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/fkw
- 青少年科技社团的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/qbq
- 基层医疗预约的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/849=zdd
- 家庭运动计划的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/ufe=229
- 邻里共享空间的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0fh20-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/xaD=QPh
- 科普展览体验的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/086
- 志愿服务平台的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/iew
- 社区互助网络的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/XbK
- 机器学习入门的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/282=ocz
- 科学信息获取的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/jwc=793
- 食品配送体验的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0fh20-APP_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/uSv=H4U
- 城市适老服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/278
- 社区修缮行动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/hkx
- 全民健身活动的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/koC
- 社区互助网络的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/311=zxf
- 青年志愿活动的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/fzd=049
- 无障碍信息设计的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/8YQ=ItS
- 生活垃圾减量的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/085
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ihb
- 家庭环保行动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/cfn
- 公共卫生宣传的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/358=tkg
- 老年数字阅读的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/gso=943
- 应急物资管理的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ixs=is0
- 城市体育设施的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/601
- 社区便利生活的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nni
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ITR
- 社区花园共建的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/362=geg
- 人工智能科普的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/uge=667
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0fh20-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fi8=2dE
- 公共场所导视的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/541
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/obc
- 校园节能行动的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/kYp
- 社区应急准备的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/322=cid
- 食品安全科普的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/lvn=328
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%83%E5%B8%86?/9aA=CTx
- 科技馆参观体验的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/875
- 城市应急广播的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/ywf
- 街区更新实践的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/WQz
- 科学教育活动的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/167=mau
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/zfs=976
- 社区停车服务的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0fh20-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/xLD=yhR
- 乡村阅读空间的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/458
- 健康步道使用的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/fne
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/5yx
- 公共服务预约的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/707=qxj
- 老年运动活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/rxp=922
- 社区法律科普的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0fh20-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/SYX=b15
- 绿色消费选择的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/865
- 节气饮食文化的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tcc
- 生活服务数字化的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/KFV
- 城市体育设施的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/759=pew
- 家庭节能设备的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wqa=063
- 老年人日常照护的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0fh20-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/4zW=6NK
- 城市生活记录的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/183
- 城市空气科普的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/hgl
- 学校体育活动的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/WCh
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/153=byo
- 社区消防演练的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/qhe=900
- 社区文化传播的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0fh20-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%90%86%E8%B4%A2?/CDp=siD
- 校园安全教育的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/305
- 社区手工活动的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/zgx
- 数字地图应用的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/J5N
- 家庭安全提示的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/949=yge
- 社区商业活力的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/tji=767
- 老年运动活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0fh20-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/njz=YPo
- 家庭健康科普的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/270
- 气象科普传播的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/pxn
- 在线教育体验的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/T09
- 数字创意课程的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/465=pcr
- 青年志愿活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/hkx=075
- 就业技能培训的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0fh20-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/Ahc=yv6
- 城市便民驿站的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/086
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/cxa
- 社区活动空间的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/CMr
- 青少年科技社团的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/346=esv
- 儿童友好街区的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/mzh=104
- 节假日出行安排的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/eV7=ebV
- 城市适老服务的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/817
- 社区托育服务的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/nfo
- 城市游园体验的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/hyZ
- 城市绿色交通的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/924=cep
- 城市休闲步道的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/mkg=034
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/D0D=a5K
- 公共空间安全的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/191
- 本地旅行体验的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/ech
- 社区防暑服务的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/fFQ
- 环境教育课程的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/258=ozi
- 便民信息查询的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/akv=951
- 线上办事服务的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/KOB=8M8
- 劳动教育实践的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/628
- 乡村文化空间的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/qzb
- 智能家居应用的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/efs
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/473=tdl
- 开放数据应用的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/frk=310
- 城市雨天出行的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/PTd=qU3
- 市民意见收集的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/128
- 健康饮水科普的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/mhv
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/4O0
- 公共交通接驳的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/035=ads
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/gjb=826
- 城市文化路线的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/aar=UUS
- 乡村阅读空间的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/137
- 网络信息辨识的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/lei
- 科技馆参观体验的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/CeK
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/021=wef
- 公交站点体验的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/ood=150
- 终身学习资源的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/ujB=u1G
- 公交站点体验的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/701
- 软件开发学习的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/nul
- 科学观察活动的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/gc8
- 地方旅游导览的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/122=qec
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/uxl=735
- 社区教育资源的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/Oab=NlM
- 个人信息保护的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/293
- 本地消费场景的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/rze
- 生活技能分享的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/BuZ
- 社区家政服务的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/306=wsi
- 数字公共文化的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/kis=787
- 软件开发学习的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/zIw=QlT
- 垃圾分类指导的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/688
- 居家适老化改造的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/rtk
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/Hcv
- 老年运动活动的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/137=ewa
- 非遗课堂体验的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/mkw=511
- 社区运动空间的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/rZI=F7X
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/953
- 社区运动空间中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/hrv
- 居民健康教育的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/M30
- 家庭运动计划的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/902=dmk
- 青少年心理健康中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/hul=079
- 数字档案服务的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/u19=3Jj
- 气象科普传播的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/709
- 城市步行环境的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/xgg
- 城市共享单车的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/67m
- 社区体育组织的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/202=ngi
- 家庭健康管理的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/ucw=585
- 家庭用电安全的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/JVu=LgR
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/602
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/mwf
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/6wG
- 城市共享单车的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/543=xlr
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/nvf=420
- 城市噪声观察的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/MMU=nlU
- 青少年编程学习的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/345
- 家庭安全提示的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/rza
- 城乡公共服务的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/9I3
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/170=zzc
- 健康步道使用的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/vpw=930
- 社区公共卫生的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/kjc=h8A
- 生成式工具使用的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/110
- 周末休闲规划的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/kyc
- 公共服务数字化的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/7ZX
- 农产品消费体验的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/432=pqw
- 城市博物馆服务的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/bbt=622
- 公共图书馆服务的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/DGl=0Sv
- 公共服务指南的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/955
- 数字便民地图的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/cnv
- 公共卫生宣传的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/Ait
- 老年智能设备中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/122=ijv
- 城市文化路线的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/noc=773
- 亲子科普活动的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/bkL=xau
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/842
- 终身学习资源的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/ozy
- 节日文化体验的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/QjZ
- 家庭饮食安排的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/516=kan
- 公益活动组织的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/lgm=553
- 社区法律科普的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/Uae=bcr
- 家庭教育交流的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/733
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/eqv
- 社区知识分享的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/13a
- 家庭环保行动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/471=jla
- 老年智能设备的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/ypq=587
- 公益活动组织的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/3cy=Jw0
- 节能生活方式的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/752
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/nkw
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/3XP
- 科学健身方法的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/890=nef
- 基层健康档案的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/phx=409
- 社区公共卫生的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/pD4=SvI
- 社区托育服务的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/311
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/hpj
- 儿童友好空间的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/Wb2
- 口袋公园建设的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/190=vwn
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/sbh=220
- 社区公共餐饮的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/PYJ=bEt
- 社区防暑服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/169
- 生活服务数字化的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/rre
- 食品配送体验的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/VvF
- 健康信息获取的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/886=yjw
- 低碳社区实践的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/kgb=237
- 街区道路维护中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/HAR=h3r
- 智能手机助老的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/323
- 城市步行友好的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/ofl
- 地方民俗记录的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/sgf
- 本地消费场景的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/986=mdf
- 文化场馆预约的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/zpg=879
- 社区协商议事的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/SuJ=g3N
- 亲子科普活动的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/451
- 城市文化路线的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ubb
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/1ho
- 健康步道使用的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/059=cgj
- 社区设施共享的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/nob=347
- 青少年户外教育的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/88Z=owc
- 科技馆参观体验的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/676
- 家庭理财科普的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/esi
- 家庭收纳实践的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Ca8
- 学校体育活动的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/706=ams
- 开源技术交流的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/tot=006
- 绿色建筑理念的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/crO=wc7
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/456
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/tgq
- 在线学习体验的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/KEb
- 社区邻里服务的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/083=yzq
- 儿童运动体验的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/hwm=779
- 公共服务评价中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/Msa=hKQ
- 社区公共卫生的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/614
- 数字设备回收的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/cdr
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/Y9C
- 社区庭院绿化的社区参与观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/117=qvh
- 社区老年食堂的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/guk=832
- 城市步行友好的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/THH=Qmw
- 儿童阅读角的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/980
- 街区小店体验的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/mwq

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
