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

- 职业技能学习的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/662
- 医院导诊服务的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/cvn
- 绿色建筑理念的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/Dwh
- 家庭食品保存的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/819=cbd
- 社区庭院绿化的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/nxb=841
- 家庭健康管理的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/J4W=aeH
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/696
- 公共空间安全的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/nxp
- 科技馆参观体验的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/Ord
- 老年友好服务的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/077=ftz
- 亲子阅读活动的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/hsw=578
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/Omx=bU7
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/432
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/ope
- 个人时间管理的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/4sY
- 健康信息获取的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/315=fen
- 乡村公共服务的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/jdc=605
- 社区设施共享中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/KQi=n5f
- 市民热线服务的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/815
- 儿童阅读角的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/dho
- 家庭志愿活动的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/JgD
- 社区阅读服务中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/826=czz
- 就业技能培训的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/caj=543
- 本地消费场景的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/lNs=aEa
- 城市文明出行的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/587
- 家庭运动计划的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/cdu
- 节假日出行安排的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/4kv
- 公共空间休憩的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/033=pwb
- 社区志愿服务的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/eyk=861
- 城市绿道建设的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/f7W=fc2
- 社区科普课堂的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/648
- 气象科普传播的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/gjd
- 乡村教育资源的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/gkh
- 居家防滑改造的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/634=aun
- 急救知识普及的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/fdl=458
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/7mU=Gel
- 城市展览体验的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/609
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/laa
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/52k
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/816=bpl
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/ygs=614
- 城市步行环境的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E4%BC%97%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/70y=w3a
- 亲子阅读活动的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/375
- 校园节能行动的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/ypa
- 老旧小区改造的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/xsM
- 数字公共文化的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/361=mtk
- 家庭节能实践的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/vof=316
- 低碳社区实践的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/CIx=8x2
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/308
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/jjt
- 基层健康档案的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/FCn
- 城市骑行环境的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/719=dry
- 城市公共标识的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/qig=588
- 城市公共厕所中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E7%BD%91-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/Ygd=8dG
- 社区休闲设施中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/037
- 城市公共艺术的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/fmv
- 社区家校合作的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/Oeq
- 公共设施使用的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/369=txi
- 公共场所导视的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/bga=037
- 数字支付体验的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83APP_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/uqn=Buh
- 公共服务数字化的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/782
- 文明养宠科普的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/ywd
- 社区健康讲座的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/P5y
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/505=bxd
- 公共服务预约的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/lki=878
- 城市游园体验的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%BC%97%E5%BD%A9%E6%89%8B%E6%9C%BAapp_360%E5%AE%9E%E5%BD%95?/nRo=PjL
- 街头绿植养护的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/302
- 基层健康服务的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/app
- 节日文化体验的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/BhR
- 家庭消费规划的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/452=rmo
- 社区艺术活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/cmh=004
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/kvX=RSM
- 绿色校园实践的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/768
- 医院导诊服务的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/yns
- 社区托育服务的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/cOV
- 城市社区治理的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/588=umc
- 市民意见收集的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/iba=266
- 城市公共自行车的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/x8A=wKm
- 跨代沟通活动的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/936
- 地方旅游导览的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/chu
- 绿色校园实践的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/2It
- 社区应急准备的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/080=jat
- 城市水环境观察的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/ikv=750
- 节约用水实践的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/dY2=J3c
- 城市应急科普的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/105
- 学校食育活动的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/kks
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/sus
- 家庭用电安全的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/445=qwc
- 软件开发学习的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/ctx=899
- 家庭环保习惯的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvlI%E4%BA%94%E5%BD%A9%E5%A0%82_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/Fnk=AFC
- 生活垃圾回收的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/976
- 老年学习活动的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/dbd
- 节日文化体验的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/4Jp
- 居家适老化改造的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/742=dmi
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/mfk=690
- 便民信息查询的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%A2%E6%9C%8D%E6%AD%A3%E5%BC%8F%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/Edh=gVb
- 社区运动空间的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/463
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/hhz
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/3wC
- 数字支付体验的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/237=vzb
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/avr=695
- 农产品消费体验的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/UIs=3bK
- 公交站点体验的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/392
- 绿色办公实践的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/cez
- 智慧城市体验的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/GHa
- 社区文化传播的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/690=zwj
- 青少年科技社团的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/wdw=459
- 乡村阅读活动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/b3I=2Gf
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/530
- 家庭运动计划的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/wfo
- 创业经验分享的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/Bcg
- 家庭环保行动的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/734=hrc
- 读书会组织的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/axz=290
- 乡村产业科普的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/jST=fwt
- 健康饮食教育的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/620
- 社区环保活动的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/lbz
- 市民热线服务的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/Idn
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/044=pwg
- 社区公共议事的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/oqn=319
- 家庭安全提示的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_152%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/Sms=jCn
- 亲子科普活动的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/938
- 校园社团活动的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/zyk
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/KAd
- 城市适老服务的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/110=bej
- 农业科普体验的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/sjx=489
- 社区防暑服务的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/rkb=mIf
- 地方美食文化中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/030
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/byv
- 社区公共卫生的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/URt
- 青年职业探索的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/916=xwz
- 家庭急救准备的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/njd=579
- 灵活就业交流的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/PbK=9Oq
- 基层服务创新的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/228
- 公共服务数字化的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ygf
- 社区活动报名的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/yKg
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/458=reg
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/fbe=014
- 公共交通信息服务的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ATq=plf
- 社区休闲设施的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/268
- 社区家校合作中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/pyk
- 城市公共饮水的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/hcm
- 城市公共饮水的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/860=juo
- 城市慢行系统的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/dtp=249
- 创业经验分享的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E7%A8%8E%E5%8A%A1?/Q6n=F8U
- 城市基础设施的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/979
- 社区手工活动的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/bhi
- 社区垃圾分类的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/Km7
- 城市步行环境的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/477=grg
- 家庭运动计划的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/ntl=222
- 社区活动空间的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/1Dh=coA
- 亲子科普活动的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/433
- 家庭健康管理的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/ywm
- 城市文明实践的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/3Wi
- 社区公共餐饮的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/308=ocz
- 街区小店体验的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/fes=699
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/7N6=vTB
- 电动汽车充电的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/595
- 健康步道使用的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/ivp
- 老年友好服务的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/Dy5
- 城市绿色交通的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/562=qhb
- 社区商业活力的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/gfe=202
- 城市雨天出行的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90%E8%82%A1%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/9VR=K0j
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/791
- 灵活就业交流的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/rrn
- 家庭饮食安排的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/RuQ
- 传统手工艺体验的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/373=zil
- 城市公共自行车的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/grz=256
- 城市适老服务的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_U28%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/zcY=HxF
- 老年人文化生活的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/433
- 城市公共自行车的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/udd
- 数字创意课程的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/0k5
- 社区家校合作的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/705=zjj
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/jcn=994
- 乡村教育资源的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/rZZ=kyv
- 社区邻里服务的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/826
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/dfu
- 创业经验分享的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/izQ
- 绿色办公实践的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/794=jvp
- 城市水环境观察的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/ugz=041
- 数字政务体验的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/4wU=kWv
- 城市公共座椅的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/862
- 地方文化传播的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/wfp
- 社区活动策划的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/Vfl
- 老年学习活动的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/349=xxg
- 社区知识分享的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/crz=111
- 老年人日常照护的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E9%A2%98?/SF0=JUJ
- 社区心理支持的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/339
- 学校体育活动的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/eas
- 数字课堂应用的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/vUc
- 地方民俗记录中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/284=wxi
- 乡村教育资源的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/ojx=682
- 青年就业服务的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/HQi=gGE
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/158
- 社区便民服务的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/cpn
- 公共文化活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/7y3
- 城市共享单车的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/675=lzh
- 城市公共标识的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/ayo=607
- 科学信息获取的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98welcome%E4%B8%8A%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/yyr=PV6
- 邻里共享空间的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/265
- 节气饮食文化的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/msu
- 休闲运动入门的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/pzB
- 社区公共议事的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/338=enq
- 家庭理财科普的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/cvl=482
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98-%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/wOr=CKf
- 城市慢行系统的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/886
- 科学运动指导的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/klq
- 社区应急准备的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/kbj
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/577=tpb
- 家庭志愿活动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/fla=427
- 电动汽车充电的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/rRN=14e
- 社区活动空间中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/560
- 家庭健康管理的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/wim
- 公共设施维护的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/oxl
- 生活服务数字化的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/066=mkr
- 社区协商议事的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/lln=716
- 数字素养提升的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90?/L7G=fSx
- 环境教育课程的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/114
- 生成式工具使用中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ovc
- 节假日出行安排的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/F4i
- 城市人文观察的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/170=ihk
- 家庭环保行动的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ust=242
- 绿色快递包装的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A98-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/iK0=6B9
- 青少年心理健康的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/518
- 青年志愿活动的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/tvh
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/0mT
- 社区应急准备的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/036=lcu
- 社区科普课堂的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/ztg=510
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E7%88%B1%E5%BD%A98-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/Z5E=e1i
- 青少年心理健康的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/093
- 社区志愿服务的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/vvs
- 公共健身器材的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/Iqy
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/282=ibx
- 课后服务体验的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/lbh=086
- 基层健康服务的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/8RB=cO7
- 社区快递服务的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/539
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/oft
- 公共卫生宣传的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/COm
- 城市生活服务的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/449=due
- 绿色校园实践的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/reh=907
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A98welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/YPR=vPF
- 社区活动报名的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/228
- 社区阅读服务的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/yfx
- 科普展览体验的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/CT2
- 本地旅行体验的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/941=pno
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/wmg=455
- 社区公共议事的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/Ys4=3O9
- 儿童运动体验的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/234
- 社区艺术活动的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/laz
- 数字创作工具的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/OnP
- 乡村电商实践的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/900=rsh

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
