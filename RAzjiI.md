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

- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/fep=967
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/u4n=0kr
- 开源技术交流的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/644
- 公共健身器材的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/fpp
- 社区邻里服务的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/sOq
- 数字支付体验的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/783=ufp
- 无障碍信息设计的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/rbe=128
- 创业经验分享中的沟通与协作 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E6%AD%BB%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/H8i=Kga
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/403
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hmu
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ugr
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/969=pvw
- 数字艺术创作的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xwr=958
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/8UA=1ID
- 文明养宠科普的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/341
- 职业技能学习的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/fyg
- 人工智能科普的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/PAE
- 公共空间导览的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/103=qib
- 乡村教育资源的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/gjg=641
- 全民健身活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/jt2=kTB
- 社区活动策划的协作机制梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/204
- 智能手机助老的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/kbq
- 健康信息获取的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/1wW
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/181=wlu
- 数字艺术创作的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/fez=749
- 科学信息获取的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/8Li=gUd
- 农业科普体验的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/606
- 消防知识宣传的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/tqb
- 本地旅行体验的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/P6U
- 终身学习资源的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/065=lfo
- 街区小店体验的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/bxk=629
- 节约用水实践的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/Xbg=zmd
- 数字政务体验的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/020
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/wwg
- 健康信息获取的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/hwd
- 家庭消费规划的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/877=udg
- 公共交通接驳的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/lwn=665
- 城市公共艺术的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/OXU=b6m
- 城市步行友好的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/469
- 亲子科普活动的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/jez
- 急救知识普及的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/gAV
- 城乡交流活动的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/027=lov
- 居家防滑改造的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/uzd=992
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/NIz=fSU
- 公益活动组织的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/202
- 社区活动报名的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/ahn
- 全民健身活动的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/Mu2
- 社区公共议事的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/282=giv
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/qfg=856
- 地方旅游导览的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8F%B7%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/9so=kEa
- 远程协作工具的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/256
- 数据分析入门的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/jdu
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/u9K
- 公园亲子设施的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/078=yej
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/lmv=569
- 全民阅读推广的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F_36%E6%B0%AA%E8%A6%81%E9%97%BB?/iNX=wx7
- 开放数据应用的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/977
- 社区体育组织中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/xyg
- 社区环保活动的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/OAp
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/000=vvi
- 运动安全知识的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/bpf=136
- 全民阅读推广的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/G5V=T0S
- 数字支付体验的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/161
- 开放式学习空间的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/mzs
- 读书会组织的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/1jH
- 数字课堂应用的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/852=lyn
- 数字公共文化的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/jjw=363
- 小区停车协商的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/0wR=yYe
- 基层健康服务的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/039
- 社区故事采集的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/emz
- 居家适老化改造的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/cUr
- 城市骑行环境的日常记录与分享 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/054=gpz
- 公共服务评价的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/yso=774
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/KMT=SEo
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/273
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/iee
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/pi7
- 数字素养提升的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/581=ksr
- 志愿服务平台的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/ijm=256
- 乡村生活观察的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/jYv=Rdm
- 数字课堂应用的安全使用提示 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/858
- 公共交通信息服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/gtf
- 地方文化传播的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/AE5
- 数字课堂应用的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/110=wjk
- 家庭环保习惯的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/zhx=399
- 骑行路线规划的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/xn0=mnK
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/039
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/ueb
- 社区家政服务的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/J7J
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/594=ryu
- 家庭节能实践的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/nla=857
- 城市微更新实践的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/Jsd=L8I
- 家庭科学教育的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/534
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/uqf
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/hGc
- 文化讲座服务的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/713=txi
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/bxu=436
- 社区邻里服务的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%8A%A8%E6%BC%AB?/TWq=6ta
- 骑行路线规划的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/226
- 城乡交流活动的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/qfc
- 本地消费场景的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/AIe
- 非遗体验活动的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/703=pux
- 社区运动空间的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/ggf=615
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/YCF=9hO
- 智慧城市体验的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/184
- 全民健身活动的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/yzo
- 家庭饮食安排的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/zh3
- 青少年科普实践的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/940=wdv
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/yqw=086
- 公共空间照明的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/4b0=D4O
- 社区宠物管理的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/512
- 生活服务数字化的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/ufp
- 公共空间安全的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/HdX
- 公共服务预约的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/063=brk
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/afb=404
- 公共文化活动的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/OID=Rx5
- 居家防滑改造的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/447
- 社区活动报名的资源利用方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/nkt
- 城市公共艺术的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/uGL
- 城市夜间照明的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/496=ive
- 公园无障碍服务的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/zfo=086
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/2wf=xPU
- 数字地图应用的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/459
- 学校食育活动的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/pnz
- 开源技术交流的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/Jrb
- 乡村阅读活动的适老服务细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/186=utg
- 社区儿童活动的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/dyx=732
- 科学运动指导的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/DJs=MKX
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/430
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/won
- 社区公共餐饮的日常使用指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/m4Y
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/405=bet
- 邻里互助活动的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/sgb=641
- 口袋公园建设的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/IL4=sYc
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/356
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/yiq
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/NL0
- 跨代沟通活动的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/324=mjp
- 非遗体验活动的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/hfy=383
- 城市便民驿站的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/xhh=Dd2
- 家庭用电安全的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/726
- 周末休闲规划的组织方法与经验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/izi
- 线上阅读资源的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/4s2
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/353=uet
- 家庭环保习惯的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/tfz=230
- 乡村阅读空间的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/CiP=ZpQ
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/934
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/dju
- 老年人文化生活的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/6O1
- 家庭急救准备的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/350=ltf
- 儿童运动体验的参与方式与路径 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/avu=935
- 公共场所导视的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/PKO=9h9
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/100
- 人工智能科普的流程优化思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/osl
- 社会体育指导的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/N16
- 健康步道使用的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/298=bkr
- 绿色出行服务的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qvn=142
- 城市住房服务的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/EE6=Pzv
- 社区活动空间的基础知识问答 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/565
- 社区活动报名的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/ojw
- 城乡交通衔接的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/a8o
- 城市绿色交通的便利性观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/552=ogy
- 骑行路线规划的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/jkr=958
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/k6E=WBt
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/504
- 老年运动活动的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/phn
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/qqk
- 社区信息发布的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/964=uwy
- 绿色出行服务的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/wcj=509
- 文化场馆预约的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/1dO=JJY
- 电动汽车充电的资源整合思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/582
- 个人时间管理的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/qdi
- 课后服务体验的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/guT
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/144=itl
- 文化场馆预约的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/txv=400
- 家庭教育交流的执行流程参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/JtW=tEA
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/493
- 家庭健康科普中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/pva
- 公交站点体验的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/9Fx
- 远程协作工具的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/548=ktv
- 物业服务沟通的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/aue=422
- 小微企业服务的便捷程度观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/mGK=4Ea
- 城市运动公园的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/179
- 街区绿化养护的居民参与机会 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/cvs
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/Hvw
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/015=cof
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/smn=666
- 数字艺术创作的学习资源整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/OHd=JKm
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/202
- 社区故事采集的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/jrx
- 街区小店体验的长期维护要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/aGX
- 城市基础设施的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/739=wxa
- 社区应急准备的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/nzz=571
- 学校食育活动的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/DKF=hIw
- 城市可持续生活的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/967
- 个人时间管理的活动体验回顾 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/nxx
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/Ckt
- 乡村阅读活动的服务细节记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/933=tpl
- 儿童户外活动的实用信息清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/ipj=632
- 节假日出行安排的空间设计要点 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%88%B8%E5%95%86?/x7N=NDV
- 智慧停车服务的常见问题梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/511
- 周末休闲规划的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/tfo
- 家庭饮食安排的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/Ec8
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/306=izv
- 城市文化路线的公共参与指南 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/dmp=937
- 城市公共饮水的服务范围梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/qq5=l6H
- 青少年心理健康的家庭实践清单 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/721
- 生活服务数字化的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/bxa
- 街区道路维护的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/1ro
- 家庭科学教育的服务信息整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/789=jwq
- 家庭健康管理的持续改进方向 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/xfw=579
- 城市噪声观察的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86PK%E6%8B%BE_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/RMF=DGA
- 个人时间管理的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/764
- 城市农夫市集的便民做法梳理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/hgt
- 城市应急科普的家庭参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/s1b
- 科普展览体验的实际需求与回应 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/087=rwa
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/yea=939
- 家庭网络使用的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/aQg=K3s
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/891
- 青少年户外教育的社区参与观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/ljg
- 校园安全教育的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/0k1
- 数字资源检索的活动策划思路 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/605=pws
- 公共空间安全的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/wdl=012
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/CAe=ZvN
- 社区手工活动的基础设施观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/105
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/adu
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/0Rg
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/131=ksm
- 公共空间休憩的服务质量观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/ajj=437
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/GAC=UR8
- 社区绿色空间的儿童友好细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/267
- 乡村生活观察的协商参与方式 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/kat
- 节能生活方式的使用门槛与改进 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/JRV
- 老年学习活动的线下体验记录 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/847=bzw
- 绿色出行服务的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/edt=515
- 小区公共照明的绿色实践方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/FbN=aPU
- 城市展览体验的日常管理方法 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/164
- 社区休闲设施的日常实践笔记 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/kfi
- 个人信息保护的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/QMO
- 社区交通安全的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/058=mko
- 社区活动策划的行动步骤参考 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/jgj=771
- 图书馆数字服务的空间使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/6Z4=vQ6
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/353
- 社区活动报名中的几个关键细节 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/dca
- 城市公共厕所的入门知识整理 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/nd1
- 社区文化节活动的常见误区提醒 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/740=fxc
- 乡村公共服务的活动组织技巧 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/vad=879
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/80M=Eye
- 垃圾分类指导的设施维护观察 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/021
- 线上办事服务的社区行动案例 |来源：https://github.com/youngvalerie3622/fadc/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/mkt

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
