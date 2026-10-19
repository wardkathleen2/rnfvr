# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:16**

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

- 城市建设科普的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/lsf=124
- 居民健康教育的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/Sby=akT
- 创业经验分享的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/636
- 社区生活指南的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/ihi
- 社区知识分享的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/oNj
- 社区共享书架的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/763=bdd
- 家庭节能设备的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/qmj=033
- 健康饮食教育中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/Gya=KiI
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/434
- 新能源出行的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/xdu
- 运动安全知识的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/px6
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/793=sfs
- 无障碍出行的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/buo=199
- 气象科普传播的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/cWb=zIm
- 老年学习活动的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/068
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/zqo
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/rKO
- 社区科普课堂的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/978=eyq
- 校园社团活动的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/mdn=627
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/Dfp=4y7
- 老年人文化生活的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/476
- 家庭节能实践的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/dna
- 城市农夫市集的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/Tx7
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/815=hzd
- 基层医疗预约的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/hkt=799
- 家庭急救准备的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/OwV=2lV
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/176
- 社区阅读服务的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/rru
- 老年学习活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/51p
- 人工智能科普的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/854=ygv
- 社区商业活力的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/pyu=321
- 数字创作工具的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/O6m=wP6
- 基层医疗预约的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/254
- 绿色校园实践的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/pcg
- 网络安全教育的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/LWq
- 本地历史资料的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/674=fzt
- 青少年编程学习的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/lgp=201
- 老年人文化生活的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/t6T=9cF
- 开放数据应用的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/010
- 数字设备回收的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/tgf
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/CG7
- 社区停车服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/807=cei
- 城市基础设施的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/wrm=928
- 家庭饮食安排的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/oII=god
- 志愿服务平台的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/096
- 家庭消费规划的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/vrm
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/aVp
- 小区公共照明的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/712=vda
- 社区文化节活动的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/zsf=787
- 老年人文化生活的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/U0x=DI8
- 绿色消费选择的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/317
- 科普展览体验的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/iuw
- 线上办事服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/HdJ
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/052=fsl
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ahn=309
- 线上办事服务的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/iEi=jZS
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/024
- 小微企业服务的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/dfa
- 乡村公共文化的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/qIt
- 城市雨天出行的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/531=zrk
- 公共设施使用的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/pku=802
- 数字支付体验的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/gIz=dNt
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/717
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/sko
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/L6z
- 社区便民集市的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/725=ikl
- 休闲运动入门的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/ldf=530
- 数字创作工具的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/IQU=rz1
- 社区停车服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/798
- 小区停车协商的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/vbe
- 智能手机助老的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/hxN
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/050=obq
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/fvt=933
- 社区故事采集的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/Dnl=fIq
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/913
- 城市住房服务的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/oio
- 生活垃圾回收的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/89L
- 小区电梯维护的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/169=nge
- 终身学习资源的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/jax=975
- 家庭理财科普的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E8%A1%8C%E6%83%85?/z6y=sX2
- 租房信息服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/551
- 社会体育指导的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/mch
- 校园社团活动的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/EPn
- 乡村教育资源的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/182=hyr
- 家庭用电安全的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/hra=492
- 社区活动空间的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/9jT=P2K
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/810
- 城市公共饮水的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/fmf
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/yY9
- 机器学习入门的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/745=bvv
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/baa=419
- 科学教育活动的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/oi7=eHo
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/486
- 绿色生活实践的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/sct
- 城市公共艺术的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/BBM
- 公共图书馆服务的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/944=whq
- 软件开发学习的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ujk=353
- 在线教育体验的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%84%84%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ZiH=Cnn
- 乡村电商实践的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/263
- 网络安全教育的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/pfu
- 城市噪声观察的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/osP
- 城市可持续生活的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/621=hjs
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/let=110
- 智慧城市体验的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/kna=3uY
- 公共服务评价的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/308
- 老年运动活动的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/nzo
- 城市骑行环境的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/Cz1
- 街道综合服务的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/870=ege
- 家庭照护支持的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/esv=017
- 农村环境治理的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/7Gj=QYi
- 新能源出行的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/598
- 健康步道使用的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/jhg
- 家庭运动计划的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/NtX
- 社区活动策划的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/806=vxm
- 青少年科普实践的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/ixn=372
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/Hi6=BGR
- 非遗课堂体验的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/810
- 运动安全知识的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/xoy
- 地方旅游导览的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/cZO
- 乡村公共阅读的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/031=azp
- 食品安全科普的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/ubq=843
- 公共服务预约的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/Fpe=tbS
- 社区阅读服务的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/308
- 社区养老服务的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/ewj
- 个人信息保护的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/M7z
- 亲子科普活动的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/126=oft
- 社区读书角建设的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/qiy=106
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/SWf=5Us
- 数字学习资源的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/904
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/oaz
- 文化场馆预约的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/MMa
- 社区家校合作的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/757=xri
- 城市公共空间的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/nnv=943
- 社区生活指南的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%84%84%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/clY=2TZ
- 乡村生态旅游的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/381
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/bpr
- 绿色建筑理念的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/F90
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/147=qpw
- 社区邻里服务的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/kow=721
- 老年人日常照护的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%84%84%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/dDq=AB3
- 邻里共享空间的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/769
- 城市展览体验的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/cme
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/9Y1
- 数字学习资源的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/257=mvt
- 健康饮水科普中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/ykr=566
- 城市人文观察的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/sY2=UiK
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/855
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/qxp
- 数字档案服务中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/mfH
- 终身学习资源的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/007=abg
- 社区快递服务的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/osn=897
- 环境教育课程的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/eDF=pl5
- 医院导诊服务的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/003
- 家庭健康科普的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/ffl
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/dHs
- 城市社区治理的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/434=eem
- 社区安全巡查的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/xit=383
- 乡村电商实践的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/dPm=D2m
- 智能手机助老的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/565
- 食品配送体验的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/yfq
- 城市可持续生活的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/0P8
- 城市水环境观察的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/793=naq
- 老年智能设备的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/awb=206
- 科学运动指导的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%90%86%E8%B4%A2?/Iv7=taa
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/318
- 社区防暑服务的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/vqp
- 绿色出行服务的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/mfr
- 社区托育服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/135=hld
- 文明养宠科普的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/sfl=142
- 数字艺术创作的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/L0Y=PO3
- 城市夜间照明的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/240
- 公共交通信息服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/kje
- 绿色出行服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/rKL
- 老年人文化生活的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/276=ctp
- 地方旅游导览的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/ccn=247
- 垃圾分类指导的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/O8M=JoL
- 社区活动策划的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/066
- 公共卫生宣传的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/hfm
- 社区绿色空间的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/6Y7
- 社区邻里服务的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/964=kdb
- 城市骑行环境的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/xmb=242
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/A2k=zCp
- 城乡交通衔接的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/848
- 劳动教育实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/tyr
- 城市绿道建设的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/J6B
- 城市社区治理的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/458=nrl
- 家庭收纳实践的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/zjg=479
- 生活服务数字化的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/HmK=vv7
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/828
- 学校体育活动的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/vqs
- 便民服务窗口的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/hCL
- 城市共享单车的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/790=isl
- 社区停车服务的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/uhh=683
- 城市绿色交通的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%90%86%E8%B4%A2?/qUp=cwg
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/447
- 社区停车服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/apd
- 绿色办公实践的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/iIA
- 日常摄影记录的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/722=ghb
- 社区共享书架的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/xiw=811
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/cVt=5m5
- 灵活就业交流的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/688
- 开放式学习空间的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/szh
- 户外活动组织的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/pzq
- 绿色出行服务的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/348=tvw
- 社区家政服务的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/mcd=866
- 社区教育资源的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/uzM=pLj
- 青少年编程学习的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/752
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/hsr
- 公益活动组织的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/6xK
- 城市公共标识的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/950=giv
- 数字艺术创作的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/vcu=383
- 城市地名文化的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E7%83%AD%E6%A6%9C?/Sgo=nHs
- 社区故事采集的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/991
- 物业服务沟通的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/lfm
- 城市微更新实践的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/dAK
- 社区科普课堂中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/183=gpf
- 城市夜间照明的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/fxq=266
- 个人信息保护的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/Cb0=nLq
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/413
- 家庭用电安全的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/tro
- 小微企业服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/wUA
- 通勤路线规划的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/027=sge
- 健康饮水科普的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/hgr=552
- 健康步道使用的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E9%A3%9F?/ipU=Zbk
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/425
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/qls
- 生成式工具使用的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/E44
- 地方文化传播的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/396=ivj
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/lgj=759
- 家庭饮食安排的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/f5V=YiQ
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/555
- 基层健康档案的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/rzv
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/v4G
- 社会体育指导的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/052=cok
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/vvt=203
- 开源技术交流的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/zIu=ksP
- 物业服务沟通的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/587
- 数据分析入门的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/rfy
- 小区停车协商的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/77f
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/728=znu
- 农业科普体验的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/ptv=127
- 基层健康服务的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/Kdv=vJu
- 家庭养老规划的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/437
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/skg
- 城市微更新实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/Lrs
- 乡村文化活动的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/678=goa
- 城市应急广播的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/efz=749
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/mud=3h4
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/798
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%84%84%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/fbh

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
