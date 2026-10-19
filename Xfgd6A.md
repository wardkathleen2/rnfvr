# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:15**

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

- 社区老年食堂的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/t83
- 公共设施使用的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/285=pnb
- 租房信息服务的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/fhm=221
- 青年职业探索的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/klq=AoK
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/240
- 公共文化活动的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/kzv
- 乡村阅读活动的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/Jlz
- 节能生活方式的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/422=uye
- 社区消防演练的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/zvq=723
- 社区共享书架的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/FtD=R4w
- 社区学习活动的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/287
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/ffe
- 邻里共享空间的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/CdY
- 家庭阅读计划的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/762=hbw
- 家庭志愿活动的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/zvt=686
- 公共卫生设施的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/5R9=b2j
- 旧物循环利用的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/332
- 骑行路线规划的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/jzd
- 学校食育活动的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/TfB
- 老年人出行服务的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/416=ror
- 数字设备回收的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/fja=982
- 儿童户外活动的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/Fz3=HYW
- 儿童友好空间的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/348
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/uzy
- 社区活动空间的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/lKU
- 社区应急准备的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/428=ejw
- 运动安全知识的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/epy=388
- 社区宠物管理的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/FhT=HX2
- 校园阅读活动的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/175
- 公交无障碍服务的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/gve
- 公共交通接驳的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/DM1
- 个人时间管理的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/849=tcm
- 城市微更新实践的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/blv=887
- 环境监测科普的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/63p=zoJ
- 家庭健康科普的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/579
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/gwd
- 街区道路维护的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/cZg
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/615=mqs
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/cvz=192
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/2RP=UjJ
- 绿色出行服务的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/944
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/avd
- 个人时间管理的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/1JP
- 课后服务体验的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/119=xls
- 城市微更新实践的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/loz=926
- 社区便民服务的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/G1E=aBH
- 社区体育组织的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/398
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/gmr
- 城乡交流活动的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/I8X
- 农业科普体验的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/511=oau
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/qfb=435
- 社区协商议事的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/adj=bsx
- 城市体育设施的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/294
- 数字创意课程的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/oje
- 智慧城市体验的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/SVi
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/365=ets
- 校园节能行动的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/zil=847
- 全民健身活动的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/18B=Htq
- 全民阅读推广的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/620
- 公共空间照明的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/dey
- 社区法律科普的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/H6v
- 社区公共卫生的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/522=kzd
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/evn=933
- 社区活动报名的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/1KC=zwm
- 绿色校园实践的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/934
- 社区健康讲座中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/lhs
- 绿色出行服务的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/v4b
- 公共服务指南的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/127=miq
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/yph=257
- 儿童安全出行的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/3K9=PcW
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/701
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/kwu
- 小区停车协商的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/lf6
- 老年智能设备的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/039=ute
- 公园无障碍服务的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/vnb=172
- 城市休闲步道的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/UVO=21r
- 城市绿色交通的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/079
- 新能源出行的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/thw
- 节假日出行安排的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/oLV
- 科学信息获取的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/278=pnu
- 图书馆数字服务的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/gwm=527
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/WiS=9Uz
- 街区绿化养护的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/741
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/gdo
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/039
- 社区应急准备的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/289=znv
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/din=933
- 社区便民服务的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/2id=6cQ
- 社区法律科普的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/053
- 公共空间照明的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/xbw
- 城市夜间照明的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/okN
- 家庭用电安全的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/974=sjz
- 社区协商议事的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/lkl=488
- 劳动教育实践的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/SZZ=nwk
- 科学信息获取的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/376
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/dpj
- 家庭收纳实践的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/Lw6
- 户外活动组织的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/216=owe
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/zmp=688
- 社区互助网络的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/xGH=JgF
- 居家防滑改造的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/100
- 便民信息查询的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/aok
- 城市步行环境的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/lQN
- 城市空气科普的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/768=spa
- 社区生活指南的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/oiz=739
- 邻里共享空间的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/FjJ=2Z3
- 家庭理财科普的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/191
- 小区公共照明的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/zda
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/RJD
- 城市生活记录的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/980=pos
- 数字生活课堂的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/ltw=714
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/rff=YNN
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/000
- 无障碍出行的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/tfz
- 街区更新实践的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/eqD
- 家庭环保习惯的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/027=dtm
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/foy=588
- 低碳社区实践的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/Ltn=9jx
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/800
- 家庭急救准备的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/sht
- 农业科普体验的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/m0t
- 城市夜间照明的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/182=rka
- 安全出行教育中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/opo=219
- 家庭养老规划的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/IKk=Kze
- 社区设施共享的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/317
- 社区垃圾回收的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/tct
- 家庭环保行动的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/6KS
- 社区老年食堂的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/973=weg
- 便民服务窗口的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/foo=277
- 城市便民驿站的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/E6C=y8V
- 科学教育活动的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/969
- 城市文化路线的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/drj
- 家庭阅读计划的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/HQn
- 城市公共自行车的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/275=jph
- 社区活动空间的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/win=434
- 社区活动报名的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/JGf=1Vr
- 社区生活指南的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/478
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/evg
- 城市建设科普的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/kSu
- 社区读书角建设的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/663=xys
- 开源技术交流的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/ugg=487
- 城市雨天出行的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/TpJ=7P5
- 节约用水实践的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/124
- 社会体育指导的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/qjr
- 青少年科普实践的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/r91
- 个人数据管理的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/285=gtu
- 乡村公共服务的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/uxa=559
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/Ory=Cf9
- 城市建设科普的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/761
- 城市步行友好的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/cam
- 基层健康服务的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/b7y
- 课后服务体验的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/373=oiz
- 数字学习资源的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/sry=340
- 地方文化传播的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP_360%E6%96%B0%E9%97%BB?/ULo=Yup
- 社区老年食堂中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/965
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/dgf
- 电动汽车充电的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/cQF
- 数据分析入门的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/865=dmf
- 家庭科学教育的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/ebe=279
- 骑行路线规划的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/yJY=wtF
- 老年友好服务的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/714
- 科技馆参观体验的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/lno
- 社区慢性病防控的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/pXm
- 城市树木认养的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/101=iog
- 健康信息获取的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/ika=368
- 生活技能分享的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/sOG=z1E
- 公共服务预约的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/093
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/jmj
- 图书借阅体验的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/jKs
- 乡村文化空间中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/383=por
- 公园休闲体验的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/pqo=140
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/TAW=Emt
- 无障碍出行的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/792
- 公共设施使用的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/tkm
- 青少年户外教育的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/96a
- 社区休闲设施的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/806=nyf
- 气象科普传播的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/oac=001
- 社区公共议事的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/2MM=6Qw
- 非遗体验活动的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/681
- 绿色出行服务的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/ujq
- 社会体育指导的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/C9W
- 社区家政服务的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/317=zgt
- 城市博物馆服务的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/nef=478
- 城市公共空间的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/ujT=awx
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/233
- 老年运动活动的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/usm
- 城市住房服务的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/GFY
- 社区安全巡查的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/583=wur
- 儿童户外活动的服务信息整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/zxt=827
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/72U=4b3
- 乡村公共文化的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/433
- 数字资源检索的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/imj
- 职业技能学习的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/RtW
- 低碳社区实践的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/894=bpl
- 社区宠物管理的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/hau=018
- 全民阅读推广的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/iHP=fk4
- 家庭理财科普的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/286
- 基层健康档案的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/aja
- 数字地图应用的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/pFM
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/865=wta
- 节气饮食文化的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/ans=386
- 文明养宠科普的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/El5=VM9
- 社区活动空间的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/115
- 社区便利生活的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/xqu
- 数据分析入门的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/zaG
- 街头绿植养护的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/565=sdr
- 公共服务指南的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/vnj=772
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/vB0=kN1
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/171
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/mvu
- 城市应急科普的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/vfg
- 公共空间安全的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/607=jkc
- 社区商业活力的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/xfb=267
- 家庭用电安全的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%91%A8%E6%8A%A5?/p5q=6Bg
- 社区法律科普的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/327
- 科学健身方法的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/ylf
- 城市公共厕所的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/8h2
- 智慧停车服务的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/662=jav
- 口袋公园建设的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/iys=568
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/BbS=9dh
- 城市生活服务的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/022
- 节日文化体验的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/aly
- 家庭养老规划的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/yw4
- 绿色生活实践的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/864=fae
- 社区公共餐饮的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/amj=993
- 城市空气科普的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/7HG=LsY
- 社区阅读服务的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/505
- 公益活动组织的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/zxl
- 绿色生活实践的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/HPn
- 生活服务数字化的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/268=ozf
- 居家防滑改造的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/bkz=871
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/n4n=e2m
- 科学健身方法中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/787
- 数字创意课程的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/vok
- 城市共享单车的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/xYk
- 老年数字阅读的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/510=isq
- 公园亲子设施的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/ecb=252
- 地方民俗记录的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/eiZ=fHU
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/327
- 乡村公共阅读的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/ofv
- 青少年编程学习的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/lIc
- 便民服务地图的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/072=gec
- 骑行路线规划的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/cnu=267
- 老年人文化生活的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/EtC=nXB
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/298
- 街区更新实践的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/paz
- 地方美食文化的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/anC
- 个人信息保护的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/394=zpu
- 城市生活服务的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/rlo=980
- 数字学习资源的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/qIP=NUu

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
