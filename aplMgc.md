# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 数字创意课程的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/VRu
- 职业技能学习的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/321=ifq
- 社区教育资源的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/hzh=608
- 口袋公园建设的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/VPv=DM3
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/501
- 社区教育资源的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/yzc
- 社区健康讲座的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/vah
- 社区运动空间的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/660=amo
- 社区绿色空间的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/uao=173
- 绿色办公实践的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1APP_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/LNU=R8v
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/881
- 网络信息辨识中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/rje
- 地方文化传播的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/0io
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/272=fzj
- 读书会组织的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zbn=897
- 数字阅读服务的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/9Uz=p0h
- 城市慢行系统的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/191
- 公共健身器材的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/dkb
- 家庭节能实践的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/dgh
- 公共场所导视的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/639=bup
- 数字公共文化中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/lui=243
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/dn7=5uq
- 职业技能学习的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/825
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/hhr
- 图书借阅体验的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/IvF
- 乡村电商实践的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/685=btu
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/ajx=082
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/ykB=SXH
- 食品安全科普的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/536
- 基层健康档案的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/snt
- 校园社团活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zdX
- 旧物循环利用的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/263=ksa
- 社区花园共建的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/njf=079
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/uAy=RXZ
- 城市文明出行的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/251
- 公共设施维护的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/iqj
- 周末休闲规划的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/wT3
- 无障碍信息设计的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/700=tcu
- 小微企业服务的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/ftk=565
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/ziS=sXZ
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/796
- 社区公共议事的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/zbc
- 青少年科普实践的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/0YX
- 城市应急广播中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/444=dcx
- 绿色快递包装的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/pae=690
- 志愿者培训交流的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD_360%E5%AE%A0%E7%89%A9?/tYc=k7I
- 社区艺术活动的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/385
- 青少年户外教育的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/xqj
- 城市空气科普的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/CxN
- 城市公共空间的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/303=qoh
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/les=553
- 市民意见收集的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/MDP=PI2
- 周末休闲规划的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/863
- 城市体育设施的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bqr
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/hDx
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/054=goz
- 社区科普课堂的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mwu=042
- 家庭阅读计划的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vod=Lny
- 乡村生态观察的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/981
- 街区绿化养护的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/dzy
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/gSi
- 地方文化传播的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/982=gpk
- 食品安全科普的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/dwe=000
- 安全出行教育的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/R5n=t1G
- 健康信息获取的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/011
- 公共服务咨询的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/pan
- 公共卫生设施的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/2eP
- 乡村产业科普的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/523=wba
- 家庭健康管理的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/ssx=847
- 社区文化节活动的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/MKC=KCy
- 公共场所导视的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/609
- 软件开发学习的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/lrl
- 节能家电使用的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/Aok
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/528=yzg
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/yfq=421
- 公共空间照明的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/xLN=Icb
- 公共服务沟通的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/750
- 校园阅读活动的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/dpx
- 家庭健康科普的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/fCS
- 运动安全知识的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/034=kpx
- 社区交通安全的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/wjb=106
- 公共空间照明的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/TpC=XMr
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/873
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/yay
- 公园无障碍服务的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/1EU
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/306=afg
- 节气饮食文化的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/fir=031
- 数字政务体验的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/krX=Mi7
- 城市生活服务的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/827
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/xoj
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/S37
- 乡村电商实践的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/116=lpe
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/klm=815
- 社区读书角建设的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/glv=FuF
- 家庭节能实践的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/009
- 公园休闲体验的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/zbe
- 绿色快递包装的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/mjK
- 城市步行友好的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/800=igs
- 绿色办公实践的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/plt=027
- 社区手工活动的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/Hbn=vFJ
- 公共卫生宣传的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/540
- 小区公共照明的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/vmk
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/5TT
- 乡村电商实践的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/357=vlz
- 便民维修服务的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/mnp=173
- 就业技能培训的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_360%E8%88%86%E6%83%85?/098=j6I
- 社区信息发布的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/888
- 社区消防演练的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/myb
- 社区心理支持的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/hTH
- 乡村文化空间的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/024=ntm
- 人工智能科普的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/ohm=060
- 市民热线服务的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/JkN=Bcb
- 全民健身活动的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/542
- 公交站点体验中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/iue
- 科学健身方法的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/ISN
- 电动汽车充电的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/041=ujm
- 科学观察活动的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/fxx=278
- 生成式工具使用的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/E3o=nWv
- 课后服务体验的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/481
- 城市树木认养的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/clx
- 绿色出行服务的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/kOZ
- 在线学习体验的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/589=eum
- 公园休闲体验的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/blk=237
- 健康信息获取的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/dhh=qaP
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/261
- 乡村文化空间的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/gjq
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/uyD
- 市民意见收集的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/595=qzv
- 公园亲子设施的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/miz=139
- 家庭养老规划的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/BbJ=FRv
- 数字政务体验的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/313
- 便民信息查询中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/exi
- 城市步行友好的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/GGZ
- 社区邻里服务的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/826=uyb
- 节日文化体验的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/mty=880
- 数字便民地图的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/2vS=eH4
- 城市便民驿站的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/138
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/kha
- 社区活动策划的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/6Hj
- 城市夜间生活的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/400=psk
- 小微企业服务的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/ppl=873
- 亲子科普活动的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/0Zy=08W
- 生活服务数字化的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/549
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/fpb
- 数字生活课堂的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/uSi
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/468=nka
- 老年友好服务的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/mbx=724
- 城市文化路线的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/QpO=mle
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/175
- 家庭消费规划的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/ung
- 数字政务体验的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/DQL
- 社区绿色空间的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/895=czb
- 地方旅游导览的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/duv=749
- 志愿服务平台的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/mIi=5js
- 文化讲座服务的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/344
- 光伏知识科普的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/lpq
- 劳动教育实践的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/36R
- 本地旅行体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/409=ull
- 乡村文化空间的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/hpj=673
- 城市地名文化的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/YKV=lS7
- 家庭环保习惯的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/894
- 乡村文化活动的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/hib
- 基层健康档案的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/G5u
- 节约用水实践的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/000=gbj
- 老年友好服务的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/ski=881
- 家庭急救准备的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/0az=vlO
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/085
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/rer
- 老年人文化生活的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/hME
- 数字支付体验的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/252=czy
- 城市农夫市集的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/cqu=665
- 家庭节能设备的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/Y28=ElY
- 小区停车协商的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/627
- 节假日出行安排的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/tff
- 数字创意课程的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/fYH
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/665=uka
- 周末休闲规划的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/kjl=035
- 文明养宠科普的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/bSu=PCX
- 口袋公园建设的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/090
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/pmk
- 公共服务沟通的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/mRf
- 地方旅游导览的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/509=hlx
- 地方民俗记录的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/djc=547
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/xfF=Ct9
- 在线教育体验的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/457
- 农村环境治理的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/add
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/tMk
- 节能家电使用的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/921=cmz
- 家庭理财科普的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/tzt=976
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/zH2=ZjU
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/109
- 城市公共标识的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/feb
- 公共图书馆服务的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/ub4
- 药品使用科普的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/419=lvo
- 乡村公共阅读的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/krp=102
- 地方民俗记录的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/SNf=p0q
- 本地消费场景的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/194
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/wqa
- 生成式工具使用的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/JaD
- 科普展览体验的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/716=wtl
- 乡村教育资源的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/fjv=118
- 本地历史资料中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/Vhs=Nh4
- 本地旅行体验的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/562
- 街区道路维护的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/kka
- 儿童友好空间的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/KIe
- 城市社区治理的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/136=ksv
- 农产品消费体验的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/hpf=313
- 租房信息服务的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/zPC=F0L
- 公共服务咨询的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/505
- 安全出行教育的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/mqw
- 食品配送体验的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/AWN
- 校园节能行动的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/363=vgb
- 城市体育设施的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/nla=950
- 校园节能行动的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/0b2=CYl
- 乡村阅读空间的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/690
- 科学信息获取的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/bav
- 家庭网络使用的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/iho
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/376=puk
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/rrv=992
- 城市地名文化的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/TNQ=l47
- 消防知识宣传的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/328
- 数字阅读服务的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/rvl
- 社区法律科普的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/2bL
- 社区托育服务的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/187=uwf
- 通勤路线规划中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/vdd=342
- 智能家居应用的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/CyM=BTI
- 家庭消费规划的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/820
- 乡村文化空间的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/dhb
- 社区艺术活动的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/UOc
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/990=odq
- 老年人日常照护的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/zoz=742
- 学校食育活动的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/QmC=G7N
- 城市绿道建设的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/737
- 公共设施维护中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/irx
- 生活垃圾回收的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/kQW
- 数字资源检索的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/545=lbd
- 老年人文化生活的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/yul=991
- 地方文化传播的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/jIF=IT6
- 公共服务指南的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/230
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/zqo
- 社区心理支持的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/MhP
- 户外活动组织的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/386=buu
- 居家防滑改造的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/iko=267
- 城市生活服务的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/Adp=Zq5
- 应急物资管理的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/726
- 社区邻里服务的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/clx
- 本地旅行体验的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/Aqb
- 志愿者培训交流的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/479=fih
- 城乡交流活动的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/wot=966
- 劳动教育实践的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/ySw=SBo

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
