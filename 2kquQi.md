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

- 社区家政服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%AE%9D%E8%B4%9D%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/nXc
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%AE%9D%E8%B4%9D%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/164=gpt
- 城市绿道建设的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%AE%9D%E8%B4%9D%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/ssf=354
- 农贸市场环境的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%AE%9D%E8%B4%9D%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/gQJ=w4n
- 社区绿色空间的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/302
- 无障碍出行的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/jpm
- 数字阅读服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/xzw
- 居家防滑改造的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/604=bjk
- 社区环保活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/yim=418
- 青少年心理健康的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/Xs6=1AX
- 基层健康档案的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/754
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/nvj
- 城市步行友好的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/ZCH
- 社区快递服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/512=htj
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/pdf=091
- 绿色消费选择的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/Mkl=jD0
- 公共场所导视的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/615
- 运动安全知识的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/ddn
- 城市公共标识的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/Vk1
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/943=kip
- 网络安全教育的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/vco=772
- 市民意见收集的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E4%B9%90%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/VxW=WWh
- 城市便民驿站的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/591
- 科学教育活动的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/rsa
- 社区体育组织的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/Anm
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/092=pro
- 老年友好服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/ulq=526
- 旧物循环利用的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/GB2=9uk
- 科学教育活动的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/424
- 城市住房服务的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/obq
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/WGn
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/096=yqw
- 图书馆活动策划的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/tnv=241
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/PZe=l0x
- 志愿服务平台的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/095
- 社区快递服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/yth
- 青少年科技社团的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/BfJ
- 环境教育课程的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/744=ivf
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/egk=296
- 健康步道使用的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/Xna=Qg2
- 环境监测科普的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/584
- 市民热线服务的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/ivn
- 农业科普体验的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/nfT
- 数字资源检索的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/200=afx
- 城市公共空间的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/xiy=584
- 小区停车协商的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_81881%E7%88%B1%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/bCb=cVR
- 绿色出行服务的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/123
- 家庭用电安全的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/xpl
- 公共空间休憩的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/6tE
- 城市运动公园的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/065=lik
- 数字创意课程的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/sgi=827
- 个人信息保护中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/mUK=Kvm
- 数字档案服务的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/740
- 老年人出行服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/rjx
- 公共空间照明的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/HF8
- 数字创意课程的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/976=jam
- 城市公共自行车的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/klu=659
- 社区消防演练的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9B%BE%E8%A1%A8_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/xyA=Xbk
- 社区科普课堂的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/467
- 环境监测科普的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/qpc
- 公共场馆服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/0aj
- 公共场所导视的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/248=chq
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/yjt=706
- 家庭节能设备中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/KBO=Bgi
- 城市公共饮水的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/074
- 老年友好服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/bbt
- 公共服务沟通的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/0nh
- 公共设施使用的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/807=ayh
- 课后服务体验的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/xco=862
- 无障碍出行的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/giR=gmU
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/370
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/rou
- 公共服务预约的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/jO1
- 电子商务服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/319=djg
- 乡村阅读空间的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/yfj=967
- 小微企业服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/E37=alb
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/387
- 无障碍信息设计的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/ihj
- 社区托育服务的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/FcC
- 家庭安全提示的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/372=ifi
- 老旧小区改造的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/pvq=360
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/yeb=wVA
- 社区老年食堂的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/705
- 食品配送体验的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/bxf
- 公共服务评价的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/xFP
- 青少年心理健康的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/813=bpg
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vxs=130
- 软件开发学习的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/6pz=t87
- 老年数字阅读的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/649
- 智慧城市体验的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/cyl
- 儿童运动体验的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/6UR
- 环境教育课程的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/493=viq
- 街区小店体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/oav=125
- 社区健康讲座的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/CTk=eWD
- 农产品消费体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/979
- 在线教育体验的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/hwh
- 家庭安全提示的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/gd3
- 公交无障碍服务的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/565=trk
- 青年职业探索的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/hli=584
- 家庭环保习惯的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/2CB=idb
- 家庭食品保存的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/931
- 学校食育活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/ubn
- 家庭消费规划的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/yD8
- 老年运动活动的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/470=lmz
- 志愿者培训交流的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/hsg=659
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/E2a=O09
- 公共设施使用的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/952
- 农村环境治理的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/nba
- 乡村文化活动的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/U1q
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/561=qde
- 市民热线服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/xeg=407
- 职业技能学习的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/JSx=jZq
- 个人数据管理的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/100
- 机器人科普活动的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/tyj
- 机器人科普活动的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/fY2
- 个人时间管理的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/480=fqt
- 青年就业服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/cbu=599
- 城市骑行环境的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A?/yOi=o8M
- 公共服务评价的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/618
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/rdh
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/odM
- 城市便民驿站的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/670=miz
- 社区教育资源的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/jil=570
- 社区活动空间的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/J3T=y3g
- 社区活动报名的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/438
- 个人数据管理的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/orz
- 个人时间管理的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/v15
- 城市基础设施的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/708=kqc
- 社区互助网络的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/udx=911
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/FA5=kYo
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/143
- 周末休闲规划的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/jge
- 青少年科普实践的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/4Nj
- 线上办事服务的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/108=erc
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/fjv=293
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/HSK=wAh
- 社区家政服务的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/563
- 健康信息获取的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/cof
- 数据分析入门的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/fvj
- 社区健康讲座的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/250=ktr
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/pkn=975
- 开放数据应用的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500%5B_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/r4r=FsH
- 小区电梯维护的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/661
- 社区互助网络的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/uel
- 光伏知识科普的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ab3
- 地方文化传播的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/790=oww
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/byl=913
- 城市公共厕所的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9vl%E5%AE%89%E5%8D%93%E7%89%88_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/JJZ=aKY
- 农产品消费体验的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/267
- 社区安全巡查的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/rro
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/RSi
- 社区文化节活动的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/069=gft
- 社区学习活动的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/nuj=652
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91III%E5%BD%A9%E7%A5%A8_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/rM1=MLo
- 农产品品牌传播的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/196
- 智能家居应用的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/tql
- 城乡公共服务的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/2sH
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/007=gbi
- 职业技能学习的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/hyb=151
- 健康信息获取的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0?/6G8=ClR
- 农产品消费体验的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/327
- 户外活动组织的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/ctg
- 便民服务窗口的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/ytn
- 亲子科普活动的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/490=tqf
- 光伏知识科普的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/jny=987
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/D2M=h4S
- 新能源出行中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/552
- 灵活就业交流的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/czu
- 社区商业活力的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/xLk
- 社区手工活动的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/139=ybv
- 青年职业探索的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/ucj=722
- 公共空间安全的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/86I=OOz
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/689
- 节约用水实践的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/yua
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/Axr
- 农贸市场环境的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/422=xvx
- 生活技能分享的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/qvw=664
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%BD%E5%BD%A99123%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/zAV=GQe
- 周末休闲规划的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/426
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/drg
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/dRi
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/262=tjb
- 数字政务体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/aqz=705
- 公共空间导览的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/Awx=OED
- 青少年科普实践的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/234
- 职业技能学习的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/nlr
- 传统节日科普的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/HlF
- 绿色生活实践中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/439=gss
- 家庭理财科普的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/yzv=353
- 老年数字阅读的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_9123%E5%A5%BD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/6Om=dIX
- 城市骑行环境的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/660
- 邻里互助活动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/bau
- 家庭消费规划的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/lJt
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/733=vnn
- 社区共享书架的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ovx=378
- 社区公共议事的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xib=r8u
- 家庭志愿活动的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/357
- 非遗课堂体验的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/swi
- 农产品消费体验的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/fYq
- 文明养宠科普的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/876=vcm
- 公益活动组织的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/cju=279
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A8%B1%E4%B9%90_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/2fd=txU
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/687
- 便民维修服务的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qij
- 数字创意课程的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/fNi
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/247=efi
- 基层健康档案的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/tnb=396
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/tVP=q3F
- 青少年心理健康的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/138
- 地方美食文化的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/zfh
- 社会体育指导的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/Gpn
- 社区学习活动的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/808=ghp
- 城市应急科普的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/bsv=466
- 创业经验分享的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/Rn8=nrw
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/507
- 社区垃圾分类的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/xvk
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/LqF
- 乡村文化活动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/984=ctj
- 节假日出行安排的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/uyf=617
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/qiO=RpQ
- 健康饮水科普的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/182
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/nth
- 城市生活服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/bn3
- 家庭志愿活动的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/414=ztf
- 公共空间安全的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/dox=189
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8D%9A%E5%AE%A2?/A7A=ujd
- 家庭节能实践的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/472
- 生成式工具使用的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/qrh
- 节约用水实践的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/g8e
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/498=fnl
- 节假日出行安排的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/hpv=592
- 食品安全科普的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/0uw=qwS
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/642
- 机器学习入门的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/izm
- 校园节能行动的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/wv7
- 社区老年食堂的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/698=eur
- 户外活动组织的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/wwp=660
- 学校体育活动的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A5%BD%E5%BD%A99123_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/aZe=uAs
- 地方旅游导览的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/894
- 生成式工具使用的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/orq
- 家庭收纳实践的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/L9F
- 居民健康教育的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/528=xqf
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/bte=636
- 城市公共自行车的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_9123welcome%E5%A5%BD%E5%BD%A9_360%E9%9F%B3%E4%B9%90?/Uyn=XuM
- 骑行路线规划的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/172
- 公共设施使用中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/sqo
- 本地消费场景的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/4Rv
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/199=xnm
- 图书馆数字服务的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/iyv=776
- 小微企业服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/oiX=9Uv

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
