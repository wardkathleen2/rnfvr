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

- 社区家校合作中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/134
- 社区活动策划的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/oaj
- 网络安全教育的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/OXr
- 数字便民地图的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/068=bcp
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/vpq=679
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/hri=tmT
- 城市应急科普的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/210
- 社会体育指导的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/urg
- 乡村文化空间的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/nZy
- 社区垃圾回收的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/619=jcq
- 城市应急科普的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/yvz=302
- 社区环保活动的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2_36%E6%B0%AA%E6%96%87%E5%BA%93?/FHi=vh9
- 公交站点体验的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/498
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/htq
- 公共卫生设施的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/SmW
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/934=sws
- 健康信息获取的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/xla=522
- 城市骑行环境的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/2Me=MPx
- 创业经验分享的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/520
- 社区教育资源的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mbn
- 城市绿道建设的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/YJf
- 城市运动公园的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/501=gdv
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jqh=511
- 开源技术交流的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/n2G=fdC
- 城市树木认养的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/050
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/fwa
- 光伏知识科普的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/bfx
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/355=fyb
- 社区心理支持的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/rqe=343
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%BF%AB3%E8%B5%B0_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/sX8=sW0
- 电动汽车充电的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/940
- 家庭健康管理的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/yhq
- 地方民俗记录的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/KMw
- 城市博物馆活动的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/326=swk
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/ptu=769
- 家庭网络使用的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93%E5%88%86%E5%BF%AB3_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/xlj=2yu
- 城市休闲步道的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/712
- 生活技能分享的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/pwf
- 城市慢行系统的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/Fb8
- 社区科普课堂的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/198=quj
- 社区设施共享的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/eol=667
- 城市文化路线的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%B8%B8%E6%88%8F_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/Q1C=m63
- 网络信息辨识的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/497
- 城市文化路线的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/wat
- 生成式工具使用的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/jdr
- 乡村公共阅读的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/201=lvx
- 家庭环保习惯的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/tsg=463
- 无障碍信息设计的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E9%A3%9E%E8%89%8710%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/S7Z=N5V
- 机器人科普活动的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/601
- 生成式工具使用的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/afd
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/ORJ
- 消防知识宣传的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/778=ybm
- 绿色消费选择的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/fzz=780
- 药品使用科普的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%9E%E6%97%B6_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/WF7=mpZ
- 终身学习资源的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/453
- 社区法律科普的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/aau
- 家庭教育交流的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/XtB
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/912=tao
- 小区电梯维护的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/atr=707
- 街道综合服务的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/kzu=CaS
- 生成式工具使用的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/615
- 乡村教育资源的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/wbr
- 城市农夫市集的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/qNy
- 城市体育设施中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/695=ovn
- 智慧停车服务的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/kdq=119
- 科普展览体验的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/Rpb=UxM
- 社区心理支持的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/695
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hxz
- 公共交通接驳的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2KP
- 科学观察活动的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/055=zbk
- 社区法律科普的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hsy=535
- 科学教育活动的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/cam=JFk
- 家庭安全提示的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/683
- 老年人日常照护的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/dmw
- 社区便民集市的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/zXC
- 社区环保活动的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/456=tnh
- 社区停车服务的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/qdc=399
- 社区心理支持的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/0AJ=0RV
- 老年人出行服务的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/260
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/aug
- 城市慢行系统的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/KRS
- 街区道路维护的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/424=eav
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/pbv=436
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/w6W=gEh
- 日常摄影记录的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/702
- 数字公共文化的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/ydk
- 社区环保活动的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/gin
- 数字支付体验的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/015=tox
- 家庭科学教育的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/zko=327
- 社区家政服务的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2app_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/FTF=0dJ
- 社区绿色空间的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/447
- 社区志愿服务的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/tgj
- 绿色校园实践的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/FgX
- 科技馆参观体验的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/591=anm
- 开放式学习空间的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/hyb=563
- 社区邻里服务的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/UDt=zsH
- 城市农夫市集的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/574
- 城市生活记录的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/pjn
- 城市博物馆服务的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/mSm
- 社区读书角建设的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/086=ugg
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/udy=877
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/EOu=fRk
- 社区安全巡查的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/231
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/xbt
- 老年运动活动的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/KqM
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/725=qja
- 智慧停车服务的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/ech=295
- 社区健康讲座中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/anN=1W5
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/318
- 社区托育服务的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/gfu
- 农产品品牌传播的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/qEI
- 生成式工具使用的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/061=lzq
- 家庭防灾准备的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/ukv=769
- 数字设备回收的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/vNx=Zdp
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/032
- 数字便民地图的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/mjl
- 个人数据管理的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/y6D
- 社区便民服务的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/633=ufa
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/vum=743
- 青年职业探索中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/NhF=e7J
- 劳动教育实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/190
- 线上办事服务的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/qgs
- 家庭消费规划的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/RDx
- 农产品消费体验的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/066=tmp
- 社区生活指南的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/vxn=343
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE%E7%9A%84_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/U1a=nxi
- 科学观察活动的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/142
- 开源技术交流的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/yma
- 终身学习资源的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/7BJ
- 小区公共照明的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/002=qyg
- 骑行路线规划的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/mah=622
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%96%E6%B6%88%E4%BA%86_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/d0k=KAD
- 图书馆数字服务的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/173
- 数字生活课堂的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/mmn
- 城乡交流活动中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/8jo
- 城市游园体验的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/117=wxt
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/mdy=490
- 城市公共座椅的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BA%97%E8%BD%AC%E8%AE%A9%E5%90%88%E5%90%8C%E8%8C%83%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/337=Z92
- 城市便民驿站的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/065
- 城市骑行环境的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/adz
- 在线教育体验的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/9kZ
- 健康步道使用的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/006=zvg
- 街道综合服务的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/kds=725
- 基层健康档案的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/tRV=0ON
- 儿童友好街区的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/531
- 城市休闲步道的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/scg
- 绿色消费选择的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/s14
- 社区阅读服务的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/542=ytv
- 乡村公共阅读的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/mek=774
- 城市雨天出行的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/NGC=OVi
- 城市步行环境的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/694
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/bik
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/Sam
- 乡村产业科普的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/658=kex
- 数字课堂应用的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/vuo=389
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8C%97%E4%BA%AC%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/eGV=9NQ
- 运动安全知识的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/254
- 就业技能培训的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/ccx
- 开放数据应用的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/NLl
- 老年人出行服务的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/143=fqv
- 城市展览体验的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/hxl=069
- 乡村生态观察的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/ySs=SbI
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/100
- 环境教育课程的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/pvk
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/KiA
- 社区设施共享中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/704=wna
- 社区活动报名的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/ynk=735
- 绿色办公实践的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/jWm=8mt
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/432
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/ddz
- 无障碍信息设计的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/F4Z
- 社区体育组织的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/307=kzm
- 公共服务评价的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/xza=824
- 社区托育服务的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/uS8=lYi
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/455
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/kao
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/Kkr
- 节日文化体验的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/104=kur
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/nrs=347
- 开放数据应用的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E5%AE%B6%E7%94%B5?/apW=2aX
- 社区体育组织的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/333
- 城市游园体验的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/rvd
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/2xx
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/730=onp
- 智能手机助老的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/myd=600
- 街头绿植养护的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/7Mw=bRK
- 城市生活服务的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/055
- 城乡公共服务的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/krc
- 职业技能学习的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/ykc
- 家庭健康管理的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/602=imh
- 城市地名文化的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/zwa=662
- 社区慢性病防控的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%88%92%E8%B5%8C%E6%89%80%E9%9C%80%E8%A6%81%E8%B4%B9%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/EOz=ZwS
- 数字公共文化的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/084
- 城市噪声观察的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/hfj
- 文化讲座服务的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/tfS
- 健康饮食教育的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/919=rrh
- 老年人出行服务的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/zri=867
- 农业科普体验的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/lui=OAV
- 公共服务预约的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/042
- 农村环境治理的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/gzy
- 无障碍出行的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/2Op
- 公共场馆服务的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/211=hao
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/tko=110
- 家庭健康管理的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/HmW=FoY
- 绿色办公实践的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/353
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/aqp
- 城市展览体验的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/PYd
- 线上阅读资源中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/543=nga
- 线上阅读资源的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/rvq=456
- 传统节日科普的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/aFg=F8x
- 小区公共照明的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/804
- 城市噪声观察的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/qby
- 城市公共艺术的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/QZU
- 社区学习活动的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/610=cbl
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/hgk=184
- 公共交通信息服务的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/9J4=uBT
- 科普展览体验的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/159
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/ege
- 社区绿色空间的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/mJI
- 社区运动空间的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/207=pue
- 生活技能分享的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/ewr=697
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/b8C=61n
- 社区文化节活动的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/365
- 社区安全巡查的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/otp
- 城市公共标识的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Ubw
- 城市基础设施中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/146=eko
- 网络安全教育中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/rqk=762
- 家庭照护支持的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/XSk=AqF
- 社区生活指南的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/938
- 智能手机助老的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/euq
- 城市社区治理的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/oDb
- 图书借阅体验的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/983=cev
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/xnc=925
- 居民健康教育的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/5xp=xyf
- 老年学习活动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/755
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/gps
- 网络信息辨识中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/fdU
- 地方美食文化的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/809=qxh
- 公共场所导视的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/rnz=834
- 乡村教育资源的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_jch%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/hkT=W1v
- 全民阅读推广的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/953
- 家庭消费规划的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/mdm
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/W2t
- 城市微更新实践的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/333=rbi
- 机器人科普活动的日常管理方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/ywd=056
- 科学运动指导的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/NCr=KrS
- 社区活动策划的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/696
- 乡村生态观察中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/eut
- 家庭健康科普的日常实践笔记 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/eMz
- 青少年心理健康中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/042=ffz

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
