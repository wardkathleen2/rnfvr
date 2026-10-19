# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 农业科普体验的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/759
- 绿色快递包装的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/swt
- 创业经验分享的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/JXu
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/333=tdi
- 软件开发学习的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/oid=204
- 智慧城市体验中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%A4%E5%87%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/phH=ach
- 学校食育活动的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/980
- 城市文化路线中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/rmb
- 城市可持续生活的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/ZzK
- 图书借阅体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/423=eyq
- 数字便民地图的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/mfz=098
- 志愿者培训交流的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/wj8=8be
- 运动安全知识的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/831
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/sle
- 社区学习活动的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/bXH
- 公园亲子设施的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/250=yxc
- 数字素养提升的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/dlc=502
- 城市夜间生活的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/miH=SYr
- 生活服务数字化的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/141
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/jso
- 文化讲座服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/zGu
- 城市基础设施的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/902=fas
- 城市公共艺术的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/ggl=584
- 公共服务咨询的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/Nut=H86
- 社区花园共建的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/873
- 个人数据管理的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ioc
- 数字地图应用的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/3JU
- 文明养宠科普的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/371=tfn
- 消防知识宣传的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ksi=553
- 安全出行教育的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%90%9D%E5%8D%9C%E7%A7%81%E8%81%8A%E5%BF%AB3%E9%AA%97%E5%B1%80_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/etO=oI7
- 亲子阅读活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/690
- 城市人文观察的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/yen
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/Rn3
- 节日文化体验的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/001=dox
- 城市步行友好的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/axd=846
- 老年人文化生活的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9D%80%E7%8C%AA%E9%AA%97%E5%B1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/gvB=3v4
- 口袋公园建设的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/431
- 社区艺术活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/fwf
- 校园节能行动的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/wRk
- 城市基础设施的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/973=icu
- 志愿者培训交流的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/zme=002
- 创业经验分享的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/3nM=HRh
- 社区艺术活动的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/343
- 公共空间安全的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/uwr
- 日常摄影记录的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/4T3
- 基层服务创新的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/300=iwb
- 社区环保活动的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/htk=477
- 城市建设科普的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/FKa=M5f
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/931
- 城市树木认养的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/yhl
- 节能家电使用的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/NNp
- 城市社区治理的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/858=sud
- 劳动教育实践的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/zag=590
- 便民服务地图的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/jhF=goc
- 社区家政服务的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/284
- 数字创作工具的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/owd
- 公共服务数字化的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/MrX
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/730=jhg
- 家庭园艺实践的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/tde=520
- 家庭防灾准备的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/m10=pVT
- 家庭节能设备的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/014
- 街道综合服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/eib
- 公共空间照明的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/cBF
- 城市生活服务的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/521=ztl
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/hkc=770
- 社区休闲设施的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/mlI=oPz
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/964
- 儿童友好空间的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/tgh
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/GQe
- 老年数字阅读的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/237=jmb
- 城市建设科普的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/myj=586
- 电动汽车充电的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/1tL=Umx
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/454
- 数字阅读服务的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/yje
- 城市骑行环境的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/tP1
- 社区生活指南的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/645=juv
- 全民健身活动的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/auz=117
- 社区便民集市的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/sLO=Q2B
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/669
- 线上办事服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/vuk
- 公共健身器材的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/JoW
- 绿色消费选择的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/370=knz
- 家庭运动计划的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/tuf=504
- 农产品消费体验的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/LbT=gbn
- 个人信息保护的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/862
- 志愿者培训交流的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/obf
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/NkP
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/089=vji
- 个人信息保护的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/anb=593
- 老年人出行服务的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/Doy=jxe
- 家庭节能实践的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/717
- 公交站点体验的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/fjy
- 社区家校合作的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/FZA
- 社区老年食堂的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/941=ape
- 青少年心理健康中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/kaf=672
- 数字创作工具的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/SJo=tE2
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/741
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/vsu
- 家庭饮食安排的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/wTY
- 绿色消费选择的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/072=dbn
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/ern=318
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/WmL=2SI
- 城市可持续生活的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/333
- 家庭照护支持的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/eio
- 健康饮食教育中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/JlW
- 社区志愿服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/900=qsh
- 城市公共自行车的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/wmi=683
- 社区文化节活动的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/XMy=63d
- 儿童安全出行的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/101
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/lzc
- 社区便民集市的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/1FF
- 通勤路线规划中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/497=gje
- 社区防暑服务的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/tzf=826
- 城市体育设施的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%95%85%E6%B8%B8?/73z=JtN
- 全民阅读推广的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/810
- 节假日出行安排的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/dps
- 社区活动空间的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/SYW
- 社区互助网络的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/794=lqy
- 社区协商议事的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/cwj=636
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E5%93%94%E5%93%A9%E6%97%B6%E8%AE%AF?/tIz=7CZ
- 社区知识分享的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/068
- 科学运动指导的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/npw
- 垃圾分类指导的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/0LK
- 食品配送体验的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/210=zfa
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/iyq=316
- 环境监测科普的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/d7E=A37
- 骑行路线规划的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/558
- 乡村生态观察中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/ikx
- 城市体育设施的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/nTy
- 社区活动策划的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/448=oal
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/rje=579
- 青少年科技社团的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/Zdp=hxf
- 线上办事服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/102
- 个人数据管理的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/tpf
- 科学教育活动的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/H7J
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/758=awl
- 城市应急广播的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/qag=506
- 家庭阅读计划的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/EpE=OYd
- 社区生活指南的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/006
- 基层健康档案的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/zcu
- 家庭环保习惯的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/2ao
- 家庭节能实践的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/021=itb
- 基层健康服务的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/ote=639
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/E9X=yff
- 公共卫生设施的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/933
- 社区教育资源的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/njz
- 城乡交通衔接的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/ZTQ
- 儿童户外活动的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/029=krg
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/dhs=010
- 街道综合服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/Rwv=IJ6
- 社区志愿服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/621
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/dmw
- 数字艺术创作的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/MgN
- 公共健身器材的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/315=rna
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/hyg=561
- 图书借阅体验的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/HbQ=3FT
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/943
- 新能源知识普及的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/ilb
- 社区艺术活动的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/Wxm
- 职业技能学习的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/070=ahc
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/jio=130
- 气象科普传播的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/tTO=q9q
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/277
- 公共文化活动中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/opj
- 休闲运动入门的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/Vqi
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/245=dvi
- 本地旅行体验的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/ltm=931
- 本地消费场景的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91-welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/Sdi=U8Y
- 儿童阅读角的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/477
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/xyi
- 科普展览体验的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/JIU
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/117=vst
- 社区文化传播的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/lcb=115
- 社区老年食堂的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7?/CNX=EQc
- 社区防暑服务的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/703
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/leq
- 安全出行教育的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/0mD
- 城乡公共服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/259=for
- 社区协商议事的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/wpx=913
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/Gh6=wLD
- 青年就业服务的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/003
- 公共空间导览的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/oxe
- 城市夜间生活的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/0z4
- 绿色出行服务的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/828=akb
- 地方美食文化的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/cgr=927
- 运动安全知识的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/528=320
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/522
- 骑行路线规划的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/jxm
- 城市文化路线的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/AuD
- 气象科普传播的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/684=nwk
- 社区菜市场服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/oio=961
- 家庭志愿活动的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/MwQ=idF
- 老年数字阅读的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/217
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/cvs
- 儿童户外活动的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/U69
- 公共设施维护的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/393=wkf
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/orr=277
- 开放数据应用的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/q1H=jds
- 社区读书角建设的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/427
- 儿童友好空间的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/ipz
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/p2q
- 公共服务数字化的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/483=hcr
- 乡村文化空间的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/umk=474
- 城市步行友好的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/VH7=K0V
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/420
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/waa
- 灵活就业交流的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/0oM
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/012=oft
- 地方文化传播的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/jzn=625
- 非遗课堂体验的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/3go=sGL
- 城市公共饮水的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/875
- 社区消防演练的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/wqd
- 数字创意课程的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/U1Z
- 城市公共艺术的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/950=ess
- 家庭用电安全的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/yvw=506
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/Hw0=EMP
- 家庭急救准备的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/664
- 社区公共议事的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/sfz
- 公共场所导视的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/FhW
- 城市步行环境中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/320=knc
- 灵活就业交流的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/knp=016
- 文明养宠科普的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Kjk=JmP
- 乡村公共服务的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/755
- 社区商业活力的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/wnv
- 个人信息保护的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/Bye
- 便民服务地图的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/036=sel
- 科学教育活动的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/ljb=889
- 街道综合服务的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/wdx=YMV
- 城市噪声观察的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/933
- 城市生活服务的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/wqt
- 校园社团活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/qeV
- 社区协商议事的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/145=abi
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/zvc=821
- 气象科普传播的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_360%E7%BE%8E%E8%82%A1?/3Ud=nHc
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/551
- 城市绿色交通的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/tab
- 智慧停车服务的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/0tY
- 科学教育活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/207=mqr
- 小微企业服务的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/yfq=503
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/P1d=H1Q
- 城市生活服务的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/072
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/yfx
- 社区科普课堂的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/U3u
- 城市噪声观察的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/917=wjw
- 数字地图应用的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/zly=479
- 在线学习体验的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/liV=KBu
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/100
- 公交站点体验中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/zpe
- 乡村文化活动的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/l3x
- 校园节能行动的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/531=wxc

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
