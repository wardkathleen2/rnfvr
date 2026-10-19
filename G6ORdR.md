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

- 家庭健康科普的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/muu=098
- 健康饮水科普的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/Agl=ti7
- 运动安全知识的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/870
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/wog
- 青年就业服务的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/sIl
- 安全出行教育的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/739=rbw
- 社区知识分享的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/nss=127
- 农业科普体验的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/HBP=z8m
- 生成式工具使用的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/630
- 社区托育服务的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/axx
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/0wo
- 社区故事采集的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/547=uxe
- 公共健身器材的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/iun=006
- 消防知识宣传的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/Bg5=75C
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/898
- 便民信息查询的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/syr
- 网络安全教育的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/h9k
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/192=max
- 数字资源检索的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/vjx=621
- 社区交通安全的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_360%E6%B3%95%E5%BE%8B?/ORM=05w
- 数字公共文化的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/748
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/poh
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/Yy2
- 基层健康档案的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/335=mkb
- 数字创意课程的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/nuh=514
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/eby=QC1
- 公交站点体验的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/988
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/etp
- 智慧停车服务的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/TzG
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/134=ity
- 节能生活方式的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/itn=309
- 便民维修服务的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/cKR=hb6
- 本地旅行体验的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/920
- 地方民俗记录的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/mvo
- 节气饮食文化中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/mjy
- 社区儿童活动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/792=qht
- 灵活就业交流的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/frc=692
- 公共服务数字化的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/q5N=S2E
- 城市应急科普的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/026
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/xnd
- 社区宠物管理的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/nUU
- 医院导诊服务的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/499=fvj
- 校园社团活动的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/xqy=317
- 消防知识宣传的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/0OH=RDX
- 医院导诊服务的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/541
- 公共空间照明的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/gxz
- 创业经验分享的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/hMD
- 便民维修服务的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/540=pjy
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/eil=206
- 口袋公园建设的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/q8d=zCW
- 数字创作工具的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/302
- 城市公共饮水的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/ekc
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/0rz
- 节气饮食文化的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/143=joe
- 城市适老服务的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/xfn=585
- 乡村休闲旅游的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/eAu=eHb
- 社区环保活动的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/211
- 城市公共饮水中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/rjg
- 校园节能行动的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ubk
- 机器学习入门的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/454=gii
- 非遗体验活动的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ldn=236
- 旧物循环利用的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/xr0=0Um
- 智能家居应用的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/085
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/qui
- 个人数据管理的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/OUO
- 老年学习活动的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/777=pjv
- 乡村生态观察的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/lka=963
- 家庭养老规划的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/SpJ=vwL
- 志愿服务平台的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/396
- 城市夜间照明的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/ruq
- 社区教育资源的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/2vh
- 城市骑行环境的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/769=yrp
- 农产品消费体验的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/acg=183
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/NEJ=Sl2
- 生活服务数字化的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/948
- 绿色生活实践的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/kkc
- 家庭防灾准备的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/EQT
- 绿色办公实践的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/666=qfh
- 节能家电使用的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/www=997
- 人工智能科普的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/uCv=m78
- 在线教育体验的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/935
- 光伏知识科普中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/ebj
- 家庭健康管理的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/WW9
- 绿色校园实践的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/563=ckq
- 图书馆活动策划的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/vzf=832
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/bG8=Ggh
- 社区法律科普的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/546
- 创业经验分享的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/wdf
- 城市公共饮水的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/jZi
- 机器学习入门的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/790=pzr
- 社区教育资源的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/goe=028
- 安全出行教育的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/8aw=KiA
- 劳动教育实践的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/870
- 城乡公共服务的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/rrv
- 学校食育活动的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/A7G
- 公共交通接驳的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/312=dea
- 社区休闲设施的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/nup=312
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/QV5=LZG
- 城市公共厕所的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/863
- 城市水环境观察的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/iul
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/u59
- 城乡公共服务的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/995=deu
- 光伏知识科普的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/ieg=348
- 骑行路线规划的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/MuT=iMc
- 全民健身活动的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/300
- 地方文化传播的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/dhw
- 家庭阅读计划的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/jtR
- 新能源知识普及的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/929=rmu
- 公共卫生宣传的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/wpe=886
- 绿色办公实践的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/F4M=1DK
- 社区健康讲座的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/819
- 本地消费场景的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/vgn
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/JM2
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/770=yui
- 城市共享单车的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/mwb=592
- 电动汽车充电的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/EV6=804
- 智慧城市体验的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/285
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/fqf
- 租房信息服务的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/IeU
- 街区小店体验的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/640=zao
- 城市雨天出行的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/mln=697
- 城市夜间照明的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/oZ4=0BL
- 社区故事采集的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/986
- 青少年科普实践的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/zik
- 社区绿色空间的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/v49
- 全民健身活动的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/681=ffj
- 乡村生活观察的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/cne=335
- 社区公共议事的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/6nQ=h12
- 青年就业服务的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/646
- 社区宠物管理中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/xrt
- 数字素养提升的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/XZs
- 老旧小区改造的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/691=iqt
- 数字艺术创作的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/img=988
- 社区手工活动的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/82f=mwC
- 社区科普课堂的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/138
- 社区公共议事的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/rxv
- 生活技能分享的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/gs7
- 本地消费场景的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/668=ysq
- 公共空间照明的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/cjs=762
- 社区手工活动中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/UpB=7wH
- 老年人日常照护的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/313
- 乡村生态观察的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ebd
- 社区手工活动的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/10O
- 社区消防演练的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/936=bkk
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/krt=867
- 公共健身器材的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jLE=AxZ
- 公共服务数字化的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/445
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/dpr
- 志愿服务平台的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/Mpu
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/269=vsi
- 文化讲座服务的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/mfq=733
- 文化场馆预约的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/Yyg=R8d
- 居民健康教育的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/538
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/pnp
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/LUJ
- 社区艺术活动中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/121=prf
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/cji=235
- 社区交通安全的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/v0M=i6s
- 智慧停车服务的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/415
- 城市生活记录的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/clq
- 数字档案服务的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/skL
- 青年志愿活动的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/952=yzj
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/wpw=382
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/uRW=7Eu
- 智能手机助老的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/383
- 亲子科普活动的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/rqd
- 乡村产业科普的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/oAF
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/406=knm
- 乡村文化活动的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/ltv=500
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/yYh=q0E
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/544
- 校园阅读活动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/udv
- 环境监测科普的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/gpZ
- 城市骑行环境的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/928=fzs
- 智能家居应用的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/zia=756
- 科学运动指导的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/JUi=HAP
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/693
- 公共服务沟通的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/dny
- 社区运动空间的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/woZ
- 节假日出行安排的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/432=rzg
- 绿色快递包装的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/ocr=707
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/rzj=jel
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/982
- 市民热线服务的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/bdm
- 公共服务评价的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/zZp
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/687=dcs
- 节假日出行安排的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/zay=742
- 网络安全教育的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/anl=3NE
- 城市慢跑路线的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/900
- 节能生活方式的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/kzr
- 校园安全教育的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/dkg
- 家庭收纳实践的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/357=euj
- 非遗体验活动的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/pzv=313
- 城市文明实践的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/Yhy=E4A
- 家庭饮食安排的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/300
- 城市微更新实践的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/lne
- 家庭健康科普的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/iJH
- 智慧停车服务的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/205=zcu
- 运动安全知识的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/knl=360
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/Vg9=jbd
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/485
- 城市展览体验的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/hrm
- 家庭网络使用的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/LTx
- 城市文化路线的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/124=qhr
- 数字创意课程的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/ocb=799
- 节气饮食文化的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/ufX=XF8
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/825
- 社区老年食堂的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/rnx
- 家庭食品保存的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/Cht
- 数字地图应用的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/970=htw
- 乡村生态观察的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/ycp=319
- 文明养宠科普的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/tEB=cHd
- 城市噪声观察的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/432
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/xcb
- 社区手工活动的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/s2P
- 社区设施共享的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/971=upw
- 乡村电商实践的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/zpa=701
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/ZYr=uQ1
- 老年人出行服务的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/708
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/svw
- 城市夜间照明的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/XvJ
- 家庭理财科普的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/578=gbh
- 物业服务沟通的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/fax=212
- 公共空间导览的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/O64=60M
- 家庭急救准备的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/874
- 开放数据应用的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/plo
- 乡村文化空间的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/68m
- 乡村公共服务的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/665=tgw
- 城市博物馆活动的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/oii=768
- 就业技能培训的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/Cjx=9Ku
- 社区绿色空间的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/950
- 数字设备回收的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/exm
- 城市树木认养的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/wKw
- 文化场馆预约的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/075=foy
- 家庭健康管理的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/fih=191
- 基层医疗预约的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/4oV=U0Y
- 城市公共标识的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/828
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/msn
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/hLW
- 科技馆参观体验的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/401=fkd
- 老年友好服务的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/khp=115
- 城市社区治理的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/a8u=RHC
- 城市可持续生活的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/350
- 家庭阅读计划的空间使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/gsz
- 社区活动策划的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/oXO
- 城市游园体验的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/512=uuy
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/dum=921
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/gkC=CpS
- 节约用水实践的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/395
- 家庭运动计划的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/lua

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
