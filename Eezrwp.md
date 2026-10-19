# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:18**

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

- 家庭饮食安排的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91__%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/vlj=759
- 休闲运动入门的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91__%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/PKL=KrG
- 乡村教育资源的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/500
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/hei
- 节能生活方式的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/Wx7
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/538=lkn
- 青少年心理健康的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/sza=513
- 职业技能学习中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%28%E7%BB%BC%E5%90%88%E7%89%88%29%E8%80%81%E7%89%88_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/Hx2=0VS
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/093
- 城市地名文化的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/kpt
- 科普展览体验的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/cqP
- 文化讲座服务的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/926=wvd
- 环境监测科普的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/bgp=288
- 智能手机助老的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/NMq=u5g
- 社区花园共建的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/560
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/bkr
- 社会体育指导的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/BlE
- 数字生活课堂的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/611=sca
- 人工智能科普的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/wmv=837
- 居家防滑改造的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E6%96%B0%E6%B5%AA_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/arX=bNN
- 社区协商议事的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/973
- 公共空间休憩的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/cvd
- 文化讲座服务中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lQ6
- 城市社区治理的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/758=awl
- 街区绿化养护的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/cto=721
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%BF%9E%E7%BA%BF_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/tjq=kSX
- 全民健身活动的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/951
- 青少年心理健康的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/kmg
- 城市空气科普的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/C66
- 青年志愿活动的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/196=rxu
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/bjv=961
- 儿童运动体验的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%AD%E5%BD%A9%E7%BD%91__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/WQj=UKT
- 公共交通接驳的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/083
- 家庭教育交流的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/wcb
- 公共图书馆服务的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/KzF
- 乡村电商实践的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/450=txw
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/acw=310
- 社区公共卫生的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/1iT=iVe
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/197
- 农贸市场环境的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/zra
- 居家适老化改造的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/fDX
- 旧物循环利用的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/918=npw
- 职业技能学习的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/mqy=042
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/Rb4=Hbm
- 城市展览体验的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/512
- 基层服务创新的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/whv
- 城市建设科普的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/cDX
- 社区活动策划的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/249=vhr
- 城市绿色交通的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/uwk=749
- 公共图书馆服务的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/fFE=GGZ
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/563
- 家庭安全提示的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/abq
- 小区停车协商的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/g1d
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/701=zmt
- 绿色消费选择的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/odd=404
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8E%92%E5%88%97%E4%B8%89%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/TxZ=rsM
- 家庭健康管理的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/316
- 家庭教育交流的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/iwk
- 社区公共议事的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/rq4
- 城市公共标识的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/561=hdd
- 社区邻里服务的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kxx=643
- 租房信息服务的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A93D%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/FfB=cNf
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/105
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/axo
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/RRx
- 线上阅读资源的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/713=brf
- 科学观察活动的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/ega=331
- 志愿服务平台的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%8E%92%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/TEL=2yX
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/040
- 社区文化节活动的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/ywl
- 物业服务沟通的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/PIV
- 城市适老服务的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/138=tlt
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/sls=537
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/gUq=cFk
- 社会体育指导的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/898
- 社区邻里服务的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/kpz
- 城市博物馆活动的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/XS8
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/801=btd
- 社区休闲设施的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/yha=825
- 城市休闲步道的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_360%E6%B1%BD%E8%BD%A6?/cVR=CMz
- 本地消费场景的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/179
- 城市博物馆服务的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/mxy
- 药品使用科普的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/q8M
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/455=xnb
- 公交站点体验的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/cgx=785
- 气象科普传播的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/WcL=48B
- 公共空间休憩的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/363
- 新能源知识普及的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/tkr
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/4xT
- 乡村教育资源的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/810=nnn
- 全民健身活动的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/kuw=893
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3d%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E7%BD%91_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/cmc=C1D
- 个人数据管理的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/198
- 城乡交流活动的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/fwf
- 地方旅游导览的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/MFq
- 市民热线服务的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/129=mox
- 校园安全教育的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/hwb=335
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_3d%E5%9F%BA%E6%9C%AC%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8%E7%BD%91_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/LeV=YYL
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/156
- 老年智能设备的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/nro
- 社区文化节活动的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/9wp
- 城市农夫市集的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/219=jny
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jbx=766
- 城市夜间生活的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A93d%E5%AD%97%E8%B0%9C%E5%9B%BE%E8%B0%9C%E6%80%BB%E6%B1%87_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/5Vs=Gsl
- 城市可持续生活的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/602
- 乡村文化空间的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/iha
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/5ex
- 小微企业服务的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/654=qxh
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/miu=019
- 青少年户外教育的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/AVU=dJH
- 城市公共座椅的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/417
- 周末休闲规划的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/vhd
- 居家防滑改造的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/kJS
- 城市农夫市集的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/204=cqe
- 物业服务沟通的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/qcm=203
- 消防知识宣传的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/WKc=Nhb
- 食品配送体验的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/986
- 公共交通接驳的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/uew
- 城市骑行环境的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/PW7
- 社区科普课堂的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/324=his
- 青年就业服务的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/wle=269
- 居家适老化改造的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/DJD=VuG
- 旧物循环利用的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/576
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/xvz
- 社区互助网络的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/s0Y
- 数字资源检索的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/357=sag
- 城市可持续生活的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/vuq=973
- 职业技能学习的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_3D%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/AK6=7Zk
- 基层健康档案的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/868
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/qkm
- 便民信息查询的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/WHD
- 城市空气科普的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/618=qrb
- 食品安全科普的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/njh=521
- 城市应急广播的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/co3=GC6
- 本地消费场景的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/997
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/lfk
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/s9K
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/881=jlv
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/mvv=552
- 城市博物馆活动的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/gmH=eMf
- 灵活就业交流的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/241
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/pue
- 开源技术交流的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/qah
- 校园节能行动的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/016=kdw
- 公交站点体验的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/lqw=716
- 社区便民服务的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/HBn=p9D
- 环境监测科普的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/581
- 读书会组织的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/cfo
- 社区花园共建中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/5IE
- 社区活动策划的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/138=xjr
- 老旧小区改造的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/xtu=798
- 城市文明出行的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/mqp=dj7
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/267
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/osi
- 城市文化路线的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/UwA
- 亲子科普活动的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/262=sme
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/yxo=790
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/V20=bbD
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/924
- 社区知识分享的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ahr
- 节能家电使用的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/GcA
- 家庭节能实践的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/885=xqm
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/sjb=484
- 物业服务沟通的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/1uT=XtK
- 城市公共厕所的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/083
- 基层健康档案的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/mdi
- 本地消费场景的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/Ugo
- 社区活动策划的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/472=eqt
- 街区更新实践的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/fqy=322
- 社区生活指南的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/fMh=9JD
- 城市公共标识的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/672
- 社区消防演练的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/etm
- 城市公共饮水的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/SOM
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/456=zer
- 街头绿植养护的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/qpi=938
- 健康步道使用的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/lb4=9h4
- 生活技能分享的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/548
- 社区环保活动的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/xfq
- 城市步行友好的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/7gb
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/400=hyh
- 城市地名文化的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/xec=167
- 城市微更新实践的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/zo6=Ye7
- 城市公共饮水的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/927
- 城市空气科普的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/whi
- 线上办事服务的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/5Qi
- 劳动教育实践的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/372=zvp
- 公共服务评价的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/ajg=181
- 绿色建筑理念的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/GdG=4hi
- 地方美食文化的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/505
- 乡村生活观察的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/nfw
- 机器人科普活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/Uoi
- 儿童友好空间的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/383=vfq
- 社区防暑服务的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/rbi=363
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/azK=inW
- 社区休闲设施的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/864
- 在线学习体验的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/dks
- 学校体育活动的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/yIs
- 远程协作工具的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/183=acy
- 家庭照护支持的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/orb=383
- 智能家居应用的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/Vk8=5xG
- 开放数据应用的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/865
- 健康饮食教育的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/rly
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/FbX
- 基层健康档案的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/074=etd
- 城市展览体验的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/wrn=525
- 图书馆数字服务的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/eN4=7T1
- 儿童户外活动的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/999
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iew
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/4GK
- 家庭运动计划的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/745=poi
- 乡村生活观察的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pds=658
- 家庭食品保存的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/g3m=uOC
- 开放数据应用的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/448
- 城市展览体验的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/zww
- 老年智能设备的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/1ZB
- 社区垃圾分类的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/893=xxx
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/duc=775
- 儿童户外活动的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/lzg=rTU
- 社区知识分享的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/380
- 数字学习资源的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/qjh
- 节假日出行安排的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/KZT
- 智慧城市体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/531=yof
- 租房信息服务的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/xnj=338
- 社区应急准备的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/j1T=0Ma
- 机器学习入门的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/662
- 食品安全科普的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/sag
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/Rw2
- 家庭运动计划的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/645=emu
- 社区菜市场服务的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/qwk=446
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/dUG=x5o
- 老年数字阅读的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/537
- 便民信息查询的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/ybo
- 社区养老服务的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/Qa8
- 数字资源检索的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/720=ewr
- 公共卫生宣传的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/lxj=144
- 城市公共厕所的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/Qhn=Ffl
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/870
- 社区文化传播的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/krj
- 市民热线服务的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/8ES
- 家庭用电安全的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/626=cfw
- 低碳社区实践中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/ofx=824
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/BND=AWo
- 数字档案服务的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/297
- 城市住房服务的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/ifo
- 家庭健康科普的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/911
- 乡村公共文化的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/897=vap
- 亲子阅读活动的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/qab=489
- 乡村文化空间的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/zss=V6L
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/924
- 社区活动策划的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/ppb

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
