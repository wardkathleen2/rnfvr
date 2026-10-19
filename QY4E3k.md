# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:19**

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

- 家庭收纳实践的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/lha=346
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/yBd=TdR
- 城市休闲步道的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/038
- 便民服务地图的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/wlx
- 数字学习资源的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/PW7
- 乡村教育资源的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/284=qrf
- 城市空气科普的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/mhk=284
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/YwT=dwW
- 无障碍出行的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/145
- 居家适老化改造的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/fwa
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/4ej
- 亲子科普活动的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/078=wdx
- 健康信息获取的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jac=233
- 社区公共卫生的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/8MA=xqp
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/857
- 城市水环境观察的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/sbg
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/p6L
- 就业技能培训的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/030=mdy
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/llj=968
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/gSf=7Fc
- 劳动教育实践的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/775
- 青年职业探索中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/syd
- 社区托育服务的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/Qvf
- 社区活动空间的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/009=xkm
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/nst=770
- 公共卫生宣传的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/nGh=DOe
- 校园节能行动的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/921
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/kfc
- 运动安全知识的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/0gS
- 家庭环保行动的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/382=tim
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/moh=604
- 城市雨天出行的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/XTk=hER
- 健康信息获取的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/316
- 灵活就业交流的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/fwe
- 节气饮食文化的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/Ylj
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/963=xft
- 食品安全科普的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/asq=779
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/YK0=tXa
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/293
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/vss
- 儿童友好空间的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/ZgR
- 社区心理支持的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/325=gxq
- 街区道路维护的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/iva=187
- 智能手机助老的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/Tok=1g1
- 公共服务预约的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/478
- 青年就业服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/lfu
- 公益活动组织的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/CvU
- 儿童友好街区的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/242=xzi
- 城市绿色交通的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/rlk=699
- 城市游园体验的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%2C%E7%A8%B3%E8%83%9C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/C22=Ori
- 环境监测科普的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/944
- 街道综合服务的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/uze
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/xcc
- 社区共享书架的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/372=bot
- 校园社团活动的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/mut=450
- 城市建设科普的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%82%85%E4%B9%90%E7%94%9F%E6%B4%BBlisa-%E5%9B%9E%E7%AD%94%E6%97%B6%E9%97%B4_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/4za=A4k
- 家庭消费规划的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/571
- 绿色出行服务的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/kcc
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/muP
- 社区交通安全的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/522=dmo
- 城市展览体验的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/eyz=859
- 家庭健康管理的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/0yv=SLk
- 绿色出行服务的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/892
- 数字公共文化的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/jzv
- 科学信息获取的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/8fe
- 公共场馆服务的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/329=kvf
- 社区艺术活动的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/jgw=091
- 绿色快递包装的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/zqd=1ZA
- 科普展览体验的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/466
- 节气饮食文化的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/thh
- 家庭安全提示的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/M6B
- 个人信息保护的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/723=vok
- 城市住房服务中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/jzc=380
- 城市基础设施的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/ZLN=1P9
- 便民服务窗口的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/358
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/cbf
- 儿童友好空间的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/R6s
- 线上阅读资源的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/662=kyq
- 老年学习活动的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/bzh=893
- 儿童户外活动的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%8F%A3%E8%AF%80_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/6Xo=4Xq
- 线上阅读资源的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/681
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/rzm
- 乡村公共文化的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/gJe
- 农村环境治理的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/543=fjz
- 城市基础设施的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/dfl=948
- 社区快递服务的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/ojs=DST
- 数字政务体验的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/542
- 城市文明出行的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/epy
- 居民健康教育的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/XTN
- 灵活就业交流中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/444=lgl
- 社区消防演练的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/rxu=950
- 食品安全科普的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/yMT=rEs
- 绿色建筑理念的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/603
- 家庭健康管理的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/ulo
- 公共卫生宣传的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/7sF
- 邻里共享空间的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/721=uto
- 城市公共座椅的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/ovd=343
- 公共场所导视的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/03d=o6j
- 城市绿道建设的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/330
- 城市共享单车的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/rhy
- 传统节日科普的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/Dl3
- 数字素养提升的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/101=bme
- 城市公共厕所的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/dho=807
- 城市绿色交通的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/5h8=cqf
- 公共服务沟通的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/745
- 城市文化路线的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/pfl
- 城市公共自行车的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/uR9
- 电动汽车充电中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/470=pyp
- 城市应急广播的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/uav=978
- 全民健身活动的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/TgP=qDX
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/223
- 急救知识普及的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/zqs
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/Mqa
- 学校食育活动的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/582=iqm
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/nnf=332
- 社区活动策划的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/oXl=YoA
- 社区心理支持的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/335
- 全民健身活动的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/sqq
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/xNL
- 社区安全巡查的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/350=xhx
- 老年友好服务的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/imx=917
- 数字政务体验的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/WxK=oxb
- 城市步行友好的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/124
- 家庭园艺实践的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/fnv
- 家庭养老规划的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/3GM
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/883=yjx
- 城市公共厕所的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/gvz=420
- 家庭防灾准备的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/Ck9=Mrb
- 街头绿植养护的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/912
- 通勤路线规划的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/kkt
- 儿童安全出行的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/wDT
- 家庭教育交流的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/015=oji
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/usv=704
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/b0E=6s4
- 乡村生态旅游的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/017
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/fwr
- 无障碍出行的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/iEq
- 个人数据管理的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/618=axg
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/btz=661
- 城乡交流活动的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/PTD=V4q
- 城市基础设施中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/392
- 环境教育课程的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/plf
- 课后服务体验的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/vkU
- 租房信息服务的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/253=ibe
- 应急物资管理的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/zby=397
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/kGv=AXE
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/754
- 社区便利生活的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/fie
- 科学运动指导的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/HKU
- 社区生活指南的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/178=pkz
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/zch=160
- 社区托育服务的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/YRC=j0y
- 数字设备回收的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/790
- 智慧停车服务的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/gtp
- 运动安全知识的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/BQU
- 数字学习资源的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/505=odq
- 志愿服务平台的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/vtu=840
- 家庭环保行动的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/yN2=IO8
- 城市雨天出行的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/327
- 数字创作工具的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/lrc
- 旧物循环利用的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/7ha
- 科普展览体验的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/138=gmk
- 校园阅读活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/sli=603
- 公共设施使用的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/YXQ=aF7
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/512
- 医院导诊服务的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/mxc
- 城市夜间照明的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/QbW
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/599=viv
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/jti=267
- 社区儿童活动的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/F0n=uhD
- 市民意见收集的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/110
- 城乡交流活动的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vyy
- 数字公共文化的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ILS
- 科技馆参观体验的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/871=gwa
- 电动汽车充电的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wnr=688
- 科技馆参观体验的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/VF7=E84
- 软件开发学习的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/265
- 节约用水实践的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/yxm
- 开源技术交流的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/nCH
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/389=dmz
- 老年数字阅读的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/sqe=321
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_360%E6%B8%B8%E6%88%8F?/BBa=GFU
- 城市树木认养的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/336
- 小区公共照明的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/mnp
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/yKt
- 公共交通接驳的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/864=bvj
- 光伏知识科普的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/urq=888
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/rhW=C3k
- 绿色办公实践的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/414
- 城市可持续生活的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/vnz
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/5PR
- 数字地图应用的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/206=pyo
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/ppn=674
- 青少年户外教育的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/4bM=vA5
- 药品使用科普的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/482
- 市民意见收集的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/mri
- 食品安全科普的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/t7e
- 公共服务评价的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/248=lsc
- 城市农夫市集的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/mla=185
- 智慧城市体验的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/6gZ=5aY
- 健康步道使用的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/016
- 本地旅行体验的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/urv
- 机器人科普活动的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/5eo
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/059=mvf
- 健康饮水科普的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/fkr=403
- 公共服务沟通的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/wcT=Mvd
- 文化讲座服务的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/582
- 传统手工艺体验的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/phi
- 社区庭院绿化的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/3J7
- 便民服务地图的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/198=iib
- 家庭消费规划的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/lyp=838
- 机器人科普活动的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/iVL=p8X
- 城市绿道建设的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/480
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/xgz
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/pqm
- 城市雨天出行的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/208=bsa
- 家庭阅读计划的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/mad=868
- 地方民俗记录的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/0eN=gYI
- 城市步行环境的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/511
- 亲子阅读活动的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/ilg
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/WRK
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/221=hsc
- 新能源知识普及的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/ujr=970
- 校园阅读活动的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/N3F=Pws
- 公共交通信息服务的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/802
- 学校体育活动的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/qky
- 机器人科普活动的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/sVG
- 读书会组织的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/499=nek
- 智慧停车服务的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/abe=745
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/WRX=7nk
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/148
- 读书会组织的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/ppr
- 公共服务指南的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/m3Q
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/859=cxw
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/des=689
- 社区安全巡查的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/a5D=SDj
- 社区宠物管理的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/726
- 数字支付体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/jgf
- 老年运动活动的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/Nss
- 社区运动空间的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/165=xhe
- 社区活动报名的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/qza=381
- 城市休闲步道的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/HdQ=QX3
- 基层健康档案的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/265
- 便民服务窗口的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/hev
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/R7j
- 家庭健康管理中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/760=fjw
- 老年人日常照护的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/njl=017
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/7Z3=8za
- 数字资源检索的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/462
- 社区商业活力的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/vby

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
