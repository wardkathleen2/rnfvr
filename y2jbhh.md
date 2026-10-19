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

- 软件开发学习的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%A2%84%E6%B5%8B%E8%A7%84%E5%BE%8B_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/wiU
- 城市雨天出行的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%A2%84%E6%B5%8B%E8%A7%84%E5%BE%8B_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/985=ird
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%A2%84%E6%B5%8B%E8%A7%84%E5%BE%8B_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/dmk=644
- 绿色校园实践的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%A2%84%E6%B5%8B%E8%A7%84%E5%BE%8B_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/OtA=RIv
- 社区快递服务的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/411
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/qvs
- 街区更新实践的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/Fdm
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/533=vwn
- 社区绿色空间的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/dlx=626
- 文化场馆预约的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E8%B7%9F%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/oxi=sBE
- 家庭阅读计划的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/761
- 智能手机助老的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/bul
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/xy1
- 城市公共饮水的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/827=jup
- 社区便民集市的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/ddb=874
- 公益活动组织的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%88%98%E4%BC%AF%E6%B8%A9%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E9%A2%84%E6%B5%8B28_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/Esw=HAa
- 亲子科普活动的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/511
- 社区公共餐饮的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/rbe
- 公共服务咨询的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ELD
- 青年志愿活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/795=rkm
- 老年人日常照护的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/skl=861
- 城市基础设施的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%A5%97%E8%B7%AF%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mfu=gR8
- 社区宠物管理的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/285
- 城市农夫市集的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/rgw
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/GY8
- 终身学习资源的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/218=elo
- 公共设施维护中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/owm=466
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E7%AE%97-%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/01o=ZHw
- 青少年户外教育的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/036
- 家庭科学教育的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/glp
- 家庭网络使用的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/lwe
- 消防知识宣传的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/150=klg
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/enm=551
- 绿色消费选择的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_PC28%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/rur=EKk
- 城市体育设施的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/864
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/qdw
- 社区协商议事的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/UWx
- 小区公共照明的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/576=aaa
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/qpz=169
- 乡村公共服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%A6%82%E7%8E%87_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/KyE=9Tp
- 绿色生活实践的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/106
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/yqo
- 休闲运动入门的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/IBh
- 公共空间导览的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/904=yvk
- 青少年科普实践的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/hmn=779
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%9C%A8%E7%BA%BF99%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/JxE=j1P
- 小区公共照明的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/374
- 社区停车服务的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/pzn
- 乡村公共文化的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/za8
- 休闲运动入门的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/895=hld
- 社区法律科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/xco=684
- 城市文明出行的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/NUD=0Yp
- 健康信息获取的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/726
- 数据分析入门的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/tec
- 城市应急广播的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/syV
- 个人时间管理的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/518=hex
- 社区防暑服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/hpq=248
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_oc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/VL1=iPM
- 城市适老服务的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/975
- 新能源出行的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/shp
- 社区健康讲座的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/Re1
- 家庭急救准备的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/403=dgw
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/oax=615
- 城市生活服务的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_1%E5%88%86%E5%BF%AB35000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/mm4=VqT
- 乡村公共服务的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/008
- 基层医疗预约的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/mol
- 家庭急救准备的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/DjT
- 便民维修服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/187=xcy
- 社区科普课堂的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/kdp=796
- 乡村教育资源的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/pt1=fiQ
- 邻里互助活动的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/914
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/xyi
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/Zfy
- 社区家政服务的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/613=dmd
- 个人信息保护的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/kos=113
- 公共服务评价的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/d3j=tPc
- 老年数字阅读中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/712
- 社区教育资源的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/sth
- 便民信息查询的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/Kkz
- 科学观察活动的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/538=uhr
- 社区读书角建设的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/mlx=709
- 亲子科普活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E3%80%81_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/UWO=IRk
- 数字阅读服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/312
- 家庭科学教育的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/wtb
- 食品配送体验的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/CRJ
- 城市微更新实践的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/330=xmr
- 生活垃圾减量的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/kqw=853
- 网络安全教育的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%83%E6%B3%95_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/WTb=ok6
- 生活技能分享的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/608
- 新能源出行的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/bfa
- 青年就业服务的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/g7N
- 本地历史资料的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/669=kkp
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/dkl=957
- 数字设备回收的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/bNF=qBv
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/776
- 无障碍出行的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/vej
- 地方戏曲体验的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/9mY
- 数字地图应用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/254=lek
- 无障碍出行的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/sja=097
- 社区托育服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/zAK=vGR
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/984
- 图书借阅体验的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/kda
- 乡村文化活动的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/SnV
- 市民热线服务的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/286=cbl
- 家庭理财科普的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/awy=615
- 城市空气科普的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_100%E5%85%83%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/yMV=bdu
- 灵活就业交流的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/453
- 个人时间管理的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/nav
- 乡村生态观察的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/TiP
- 乡村生活观察的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/615=pee
- 公共设施使用的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/szj=605
- 社区设施共享的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/Djd=yrI
- 节能家电使用的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/213
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/lxk
- 城市文明实践的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/RRK
- 绿色消费选择的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/430=anb
- 医院导诊服务中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/ekg=068
- 社区绿色空间的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/viG=QK0
- 学校体育活动的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/440
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/jfb
- 小区电梯维护的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/4wW
- 乡村文化空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/133=hoy
- 社区艺术活动的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/twb=087
- 数字阅读服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/w0a=qZ5
- 青年志愿活动的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/619
- 气象科普传播的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/lhu
- 社区快递服务的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/swP
- 户外活动组织的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/860=bya
- 城市噪声观察的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/axj=058
- 市民意见收集的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/SI0=Vqm
- 城市公共自行车的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/037
- 家庭阅读计划的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/xsz
- 绿色建筑理念的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/a5z
- 乡村教育资源的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/357=rbw
- 家庭理财科普的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/hfu=434
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/owk=28E
- 家庭安全提示的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/414
- 光伏知识科普的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/ktn
- 社区环保活动的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/Qdi
- 乡村教育资源的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/585=ktc
- 家庭阅读计划的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/yft=644
- 家庭环保行动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%98%AF%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%87%BA%E6%9D%A5%E7%9A%84_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/pRQ=RzI
- 城市噪声观察的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/720
- 数字政务体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/ccw
- 家庭健康管理的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/FMZ
- 非遗体验活动的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/277=dfz
- 非遗体验活动的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/lqd=487
- 科学观察活动的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%87%86%E7%A1%AE%EF%BC%8F_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/NEk=8wM
- 社区互助网络的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/913
- 家庭饮食安排的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/ooj
- 线上办事服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/3Ot
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/923=xpe
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/eun=708
- 便民服务窗口的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/IXo=dVC
- 老年数字阅读的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/599
- 便民服务地图的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fwl
- 城市生活服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wDT
- 公园亲子设施的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/648=dkd
- 社区交通安全的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xqu=053
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/APu=tnf
- 小微企业服务的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/967
- 城市便民驿站的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/mat
- 城市文明出行的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Tli
- 本地消费场景的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/172=kcv
- 开放式学习空间的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/rzb=670
- 青少年心理健康中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3._%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/CID=kC7
- 光伏知识科普的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/742
- 读书会组织的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/npd
- 社区交通安全的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/woV
- 城市博物馆活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/461=rmb
- 生活服务数字化的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/rna=200
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/Jq7=95u
- 非遗体验活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/725
- 城市噪声观察的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/vrc
- 城市社区治理的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/XRW
- 城市游园体验的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/300=ovi
- 城市建设科普的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/oer=129
- 公共场馆服务的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/AHw=pFC
- 数字政务体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/186
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/rsf
- 文化讲座服务的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/0EJ
- 本地历史资料的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/870=zst
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/pwk=630
- 社区环保活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%92%8C%E5%80%BC%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/z3c=QqD
- 数字设备回收的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/329
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/dcv
- 非遗体验活动的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/NPA
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/296=flm
- 绿色办公实践的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/kgv=556
- 城市慢跑路线的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/ldM=qHz
- 农业科普体验的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/978
- 城市公共座椅的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/sxq
- 社区邻里服务的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/5Di
- 地方民俗记录的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/221=fhi
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/uee=878
- 社区养老服务的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/JZT=Tdg
- 老年人文化生活的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/407
- 城市适老服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/jpt
- 社区活动报名的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/NYe
- 学校食育活动的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/734=hoz
- 城市博物馆活动的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/ite=298
- 城市共享单车的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/GS4=gNz
- 乡村生活观察的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/269
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/yzo
- 街区小店体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/7QE
- 老年友好服务的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/781=acd
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/pfh=530
- 城乡交通衔接的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/XXV=h9L
- 食品安全科普的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/378
- 街头绿植养护的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/zxe
- 绿色建筑理念的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/3Vp
- 老年人日常照护的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/617=llq
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/qud=401
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/nOd=oNC
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/694
- 家庭环保行动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/qvy
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/0Xo
- 在线教育体验的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/983=huu
- 社区花园共建的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/dhk=924
- 便民服务地图的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/9pg=aiU
- 城市绿色交通的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/976
- 城市社区治理的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/itv
- 数字创意课程的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/LCy
- 网络安全教育的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/206=ful
- 校园社团活动的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/cba=303
- 数字课堂应用的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/QXU=jR6
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/335
- 小微企业服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/xvd
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/NFJ
- 家庭园艺实践的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/732=sdw
- 社区公共卫生的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/gqb=134
- 非遗体验活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/3fG=If4
- 基层健康档案的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/160
- 周末休闲规划的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/hsc
- 社区应急准备的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/lU5
- 社区宠物管理中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/826=ukf
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/rce=264
- 城市骑行环境的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/jJQ=9Km
- 志愿服务平台的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/778
- 基层服务创新的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/tnv
- 社区托育服务的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/bZz
- 社区消防演练的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/498=tsg
- 药品使用科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/jnw=416
- 公交站点体验的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/jS0=En1
- 城乡交流活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/470
- 健康信息获取的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/ojj
- 城市基础设施的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/dnX
- 城市休闲步道的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/872=gwg
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/mad=669
- 家庭安全提示的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/X8I=XEa

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
