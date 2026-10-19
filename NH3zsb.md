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

- 文化遗产保护科普的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/280
- 公益活动组织的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/fcf
- 绿色办公实践的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/XfN
- 科学健身方法的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/088=lyt
- 科普展览体验的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/oyx=067
- 城市绿道建设的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/hDW=R9T
- 城市文化路线的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/127
- 创业经验分享的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/hdb
- 电动汽车充电的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/Xcj
- 公共图书馆服务的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/702=fue
- 公共交通信息服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/spd=968
- 校园社团活动中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_733%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/C4I=pQF
- 地方文化传播的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/918
- 城市空气科普的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/neq
- 公交站点体验的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/Pj8
- 城市夜间照明的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/290=wku
- 公共空间休憩的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/wlh=477
- 社区共享书架的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/eN8=wcu
- 志愿服务平台的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/774
- 乡村产业科普的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/swm
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/zwj
- 乡村文化活动的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/442=pbh
- 小区公共照明中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/rhb=647
- 社区儿童活动的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_733%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/ryO=7Kw
- 生活垃圾回收的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/716
- 社区便利生活的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/hms
- 运动安全知识的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/0r7
- 亲子科普活动的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/196=wtt
- 城市农夫市集的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/eij=946
- 家庭消费规划的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/1pm=wZ2
- 城市公共标识的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/756
- 职业技能学习中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/chk
- 城市雨天出行的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/3y7
- 城市博物馆服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/144=pzj
- 绿色消费选择的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/uqd=521
- 本地消费场景的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_733%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/5e3=67h
- 读书会组织的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/141
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/cjt
- 城市适老服务的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/QER
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/757=dis
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/qtx=130
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_733%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/glv=NuF
- 数字资源检索的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/442
- 居家适老化改造的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/muk
- 城市住房服务的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/F02
- 数字设备回收的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/379=hge
- 城市住房服务的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/ozw=958
- 健康信息获取的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/Pc6=Khz
- 家庭消费规划的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/002
- 社区志愿服务的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/ftu
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/8sm
- 地方文化传播的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/237=bgj
- 公共服务指南的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/nar=688
- 街区道路维护的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/Fsa=sHH
- 城乡交通衔接的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/975
- 城市社区治理的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/exc
- 乡村电商实践的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/emq
- 数字资源检索的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/882=qng
- 数字政务体验中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/xec=511
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/fei=tX3
- 城市可持续生活的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/583
- 社区停车服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/fsx
- 城乡交流活动的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/Xeg
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/828=bob
- 城市水环境观察的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/gmz=816
- 数字创意课程的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/B7v=Ua8
- 社区垃圾回收的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/430
- 社区运动空间中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/sfn
- 科普展览体验的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/DaB
- 社区儿童活动中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/931=jee
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/fxj=176
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/5eP=Z4h
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/174
- 公共文化活动的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/qlk
- 生活垃圾回收的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/HFN
- 社区停车服务的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/197=cyf
- 节日文化体验的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/lmq=889
- 智能家居应用的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/Y4T=ntj
- 社区停车服务的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/279
- 文化讲座服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/dnm
- 数字政务体验的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/Qrm
- 社区家政服务的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/742=qov
- 便民维修服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/kod=476
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/4Ir=IZz
- 家庭养老规划的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/437
- 公共设施使用中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/pyy
- 老年数字阅读中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/w1F
- 社区协商议事的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/547=izy
- 老年智能设备的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/stx=224
- 老年人日常照护的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/ncX=Iaj
- 城市夜间生活的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/643
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/vzh
- 网络信息辨识的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/YOb
- 图书馆数字服务的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/444=hnu
- 公共图书馆服务的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/fce=391
- 城市便民驿站的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/8No=JQt
- 社区家校合作的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/889
- 街头绿植养护的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/dbt
- 社区科普课堂的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/P83
- 健康步道使用的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/923=mua
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/xqa=429
- 社区互助网络的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/fYX=gtO
- 电动汽车充电的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/901
- 绿色快递包装的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/hve
- 数字资源检索的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/MaN
- 城市步行环境中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/192=pbk
- 家庭健康管理的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/ghj=560
- 垃圾分类指导的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/EcJ=1Ox
- 城市噪声观察的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/297
- 社区阅读服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ucs
- 老年人出行服务的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/3I1
- 健康饮水科普的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/115=xzc
- 家庭节能实践的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/iqa=211
- 物业服务沟通的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/9ON=cjB
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/224
- 公益活动组织的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/mwh
- 节约用水实践的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/h3x
- 乡村教育资源的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/312=qnx
- 社区公共卫生的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/mrs=575
- 公共设施维护的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_75%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/itT=C3g
- 科学运动指导的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/405
- 公共场所导视的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/xzl
- 骑行路线规划的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/FAw
- 公共空间照明的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/759=ysb
- 终身学习资源的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/rrt=891
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/CKo=6ku
- 城市博物馆服务的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/833
- 老年友好服务的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/gep
- 智能手机助老中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/XF2
- 城市夜间照明的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/164=mqo
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/agl=257
- 城市噪声观察的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/M0i=VgI
- 街区绿化养护的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/406
- 社区便民集市的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/jan
- 乡村生态旅游的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/EUJ
- 智能家居应用的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/910=bwy
- 科学运动指导的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/ldd=220
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/o1o=cx5
- 校园社团活动的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/074
- 新能源出行的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/ofz
- 数字档案服务的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/e7E
- 市民热线服务的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/454=qvr
- 本地历史资料的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/dch=416
- 节约用水实践的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_75%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/ffv=DBv
- 健康饮食教育的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/563
- 健康饮食教育的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/acq
- 家庭运动计划的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/nIk
- 城市公共饮水的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/988=qyf
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/jup=858
- 社会体育指导的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_75%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/5HE=9V8
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/523
- 公共文化活动的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/aip
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/5Rq
- 城市适老服务的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/154=ftk
- 社区活动空间的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/vte=616
- 小区公共照明的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/kLQ=WRd
- 劳动教育实践的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/826
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/yhe
- 社区活动策划的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/sw1
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/612=bab
- 农产品消费体验的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/psh=278
- 家庭食品保存的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/Jjs=DgH
- 网络信息辨识的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/449
- 社区便民集市的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/hzh
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/4kD
- 安全出行教育的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/282=gka
- 校园节能行动的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/tkh=749
- 街区小店体验的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_75%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/UC3=oKm
- 城市步行环境的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/922
- 社区运动空间中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/qlb
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/Pbn
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/554=sjf
- 家庭食品保存的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/cln=257
- 公共设施维护的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/uxS=JWA
- 本地旅行体验的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/094
- 开放式学习空间的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/xsb
- 学校食育活动的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/hPu
- 急救知识普及的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/623=gcs
- 城市生活服务的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/hce=398
- 家庭理财科普的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/ENb=YkL
- 职业技能学习的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/413
- 城市雨天出行的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/ewz
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/ktb
- 社区家政服务的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/204=yrx
- 公共服务指南的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/kaq=203
- 老旧小区改造的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/x57=Gxb
- 居家适老化改造的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/932
- 城市基础设施的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/gmu
- 公共服务沟通的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/nMV
- 社区活动空间的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/374=lkr
- 数字创意课程的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/gnm=355
- 节假日出行安排的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/2Tn=S7d
- 网络安全教育的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/180
- 社区文化传播的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/wzb
- 急救知识普及的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/Ut7
- 绿色校园实践的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/159=wqp
- 数字档案服务的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/zmv=857
- 城市公共饮水的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_360%E5%8C%BB%E8%8D%AF?/Dpa=mmQ
- 文明养宠科普的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/502
- 公共空间安全的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/lkt
- 青少年编程学习的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/fQ7
- 数字便民地图的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/408=iyi
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/sff=340
- 数字学习资源的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/A2D=Qrz
- 社区环保活动的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/979
- 公园亲子设施的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/urm
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/rV1
- 城市噪声观察的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/486=arv
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/bdb=396
- 校园阅读活动的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/Ep5=fuV
- 城市基础设施的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/964
- 学校食育活动的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/jtq
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/ffi
- 城市公共厕所的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/758=obz
- 城市步行环境的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/dme=094
- 社区活动空间的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/sO4=Qzj
- 公共空间休憩的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/867
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/zca
- 社区家校合作的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/y5E
- 数字便民地图的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/660=gag
- 市民热线服务的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/yoi=828
- 农村环境治理的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/pmd=m3l
- 城市步行友好的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/643
- 社区手工活动中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/uyl
- 城市可持续生活的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/N1D
- 老年友好服务的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/835=vdu
- 消防知识宣传的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/kci=320
- 数字素养提升的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/zru=8B8
- 基层医疗预约的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/012
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/mgh
- 居家防滑改造的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/LU4
- 社区文化节活动的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/265=vyo
- 节假日出行安排的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/jrv=348
- 公共空间照明的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/ePF=UnE
- 基层健康服务的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/857
- 数据分析入门的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/szg
- 科学观察活动的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/jGi
- 社区手工活动的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/690=zbb
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/yyi=557
- 家庭照护支持的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/Rdv=eI4
- 绿色快递包装的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/766
- 公共服务预约的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/dfb
- 校园节能行动的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/rtd
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/173=kro
- 节能生活方式的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/ntt=641
- 社区慢性病防控的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/RhZ=vgl
- 节气饮食文化的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97?/905
- 城市噪声观察的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97?/gtj
- 基层医疗预约的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97?/3Sz
- 线上阅读资源的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97?/042=wxy

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
