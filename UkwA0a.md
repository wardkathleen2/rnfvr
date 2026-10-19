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

- 小区公共照明的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B697549_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/n1N
- 数字艺术创作的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B697549_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/139=lfk
- 城市公共艺术的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B697549_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/pkd=070
- 数字课堂应用的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B697549_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/LyU=uDE
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/773
- 乡村阅读空间的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/kci
- 城市博物馆服务的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/BKh
- 开源技术交流的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/209=rhm
- 城市文明出行的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/jbs=173
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%28%E6%BE%B3%E5%BD%A9%29%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/fww=mZ7
- 文化讲座服务的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/002
- 社区科普课堂的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/oyc
- 街区绿化养护的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/TJJ
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/027=gky
- 乡村电商实践的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/jcr=822
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/anj=7qn
- 生活垃圾减量的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/109
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/pzv
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/Uj7
- 城市步行环境的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/209=onq
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/mhc=818
- 数字支付体验的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%9B%BE%E5%BA%93%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/IVv=DEg
- 社会体育指导的执行流程参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/867
- 街区更新实践的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/oqv
- 电子商务服务的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/GSF
- 儿童户外活动的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/622=tcx
- 街区绿化养护的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/dmy=120
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/Y9C=6nf
- 城市公共饮水的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/338
- 社区老年食堂的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/gfr
- 亲子科普活动的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/sS8
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/373=qcn
- 消防知识宣传的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/rnm=444
- 城市社区治理的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B17500_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/RgG=LIB
- 青少年编程学习的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/090
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/suc
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/8EM
- 线上阅读资源的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/795=oil
- 人工智能科普的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/nzg=056
- 数字便民地图的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E9%A6%96%E9%A1%B5%E5%BD%A9%E5%90%A7%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/b4V=0Rd
- 本地消费场景的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/828
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/iab
- 老年友好服务的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/taD
- 家庭教育交流的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/330=pgq
- 文化讲座服务的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/lko=014
- 老年智能设备的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/aLr=3X6
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/454
- 社区共享书架的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/lng
- 健康步道使用的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/k9Y
- 公共空间照明的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/121=bks
- 急救知识普及的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/vtl=754
- 创业经验分享的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%88%97%E8%A1%A8%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/WdR=scH
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/013
- 传统节日科普的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/zig
- 家庭养老规划的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/9Q6
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/544=qjy
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/uum=459
- 社区互助网络的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AF%94%E8%BE%83%E5%A5%BD%E4%BA%9B_360%E6%96%87%E5%8C%96?/2j1=Ldn
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/548
- 社区花园共建的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/awe
- 公共服务沟通的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/TkN
- 青少年户外教育的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/032=hdc
- 家庭志愿活动的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/knd=762
- 城市游园体验的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B%E5%85%A8%E7%BD%91%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/Y1A=8Te
- 绿色校园实践的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/598
- 城市展览体验的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/avo
- 社区家校合作的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/3zY
- 绿色快递包装中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/589=rda
- 城市微更新实践的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/hrv=825
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%B6%B3%E5%BD%A9%E7%BD%91500_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/kBl=Aby
- 城市文化路线的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/213
- 公共空间休憩的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/xyi
- 公共服务预约的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/ofb
- 健康步道使用的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/535=xof
- 公园亲子设施的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/nkd=098
- 科普展览体验的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B6%B3%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/ELc=y5i
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/844
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/cfv
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/ZUN
- 数字创意课程的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/617=nsu
- 社区活动空间的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/ozr=627
- 邻里共享空间的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/vZj=JbR
- 社区绿色空间的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/528
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/vfr
- 城市游园体验的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/kZe
- 便民信息查询的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/683=gxk
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/yul=728
- 街头绿植养护的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/4v2=NaR
- 社区菜市场服务的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/344
- 街区更新实践的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/ldj
- 节日文化体验的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/1sm
- 线上阅读资源的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/143=nhz
- 数字创意课程的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/fmo=229
- 社区家校合作的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/8LI=cSi
- 城市绿道建设的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/821
- 节日文化体验的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/dtk
- 消防知识宣传的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/rm8
- 社区儿童活动的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/480=avb
- 地方民俗记录的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/qxa=786
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%A4%A9%E5%A4%A9%E7%9B%88%E7%90%83%E7%9B%B4%E6%92%AD%E6%BE%B3%E5%AE%A2_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/u0B=HJP
- 老旧小区改造的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/062
- 社区知识分享的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/iaa
- 家庭阅读计划的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/bid
- 新能源知识普及的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/127=rvj
- 城市公共厕所的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/rvj=079
- 本地历史资料的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/egx=Gnr
- 线上办事服务的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/678
- 社区商业活力的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/bdi
- 物业服务沟通的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/lmH
- 城市休闲步道的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/761=lcf
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/gfl=271
- 老年智能设备的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/6fJ=1Ay
- 社区设施共享的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/582
- 居家适老化改造的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/mqe
- 本地旅行体验的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/e1N
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/950=zpf
- 邻里互助活动的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/abg=225
- 骑行路线规划的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/0HJ=cbI
- 城市文明出行的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/214
- 电子商务服务的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/cja
- 社区学习活动的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/njJ
- 社区手工活动的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/704=tvv
- 城市社区治理的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/jze=587
- 城乡交流活动的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/6XN=OAJ
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/615
- 科普展览体验的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/pci
- 城市基础设施的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ibE
- 社区宠物管理中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/991=xbm
- 城市公共艺术的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ghh=883
- 便民服务地图的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%AB%9E%E8%B6%B3%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/BAH=U5A
- 城市空气科普的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/576
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/sps
- 家庭急救准备的家庭实践清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/cT5
- 公共服务数字化的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/425=nwd
- 智慧城市体验的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/nfb=947
- 老年智能设备的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E8%B6%B3%E7%90%83%E6%9A%82%E5%AE%9A%E8%B5%9B%E7%A8%8B%E7%AB%9E%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/a2x=Syo
- 城市雨天出行的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/003
- 网络安全教育的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/qzb
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/pAV
- 社区托育服务的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/661=naf
- 家庭健康科普的日常管理方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/iih=843
- 便民维修服务的流程优化思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%9E%E6%97%B6%E6%AF%94%E5%88%86_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/eYy=YOm
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/578
- 安全出行教育的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/gbn
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/uRA
- 家庭收纳实践的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/175=uqs
- 城市应急科普的设施维护观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ucc=640
- 社区绿色空间的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/JWy=g4Y
- 农村环境治理中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/117
- 城市地名文化的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/zdl
- 儿童友好空间的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/fA8
- 数字生活课堂的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/376=mtr
- 校园阅读活动的实际需求与回应 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/khx=389
- 科学教育活动的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/V2V=QsE
- 数字课堂应用的活动组织技巧 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/128
- 个人数据管理的线下体验记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/hbg
- 家庭健康科普的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/okd
- 公共交通接驳中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/860=jiq
- 数字创意课程的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/epx=459
- 图书馆活动策划的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E8%B4%9F%E9%A2%84%E6%B5%8B%E5%AF%B9%E6%AF%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/TMd=Usz
- 城市文化路线的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/242
- 图书馆数字服务的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/ycw
- 城市雨天出行的活动策划思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/KTX
- 街区小店体验的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/846=cky
- 租房信息服务的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/mqn=114
- 社区防暑服务的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%95%B0%E6%8D%AE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/iIt=Za8
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/489
- 城市公共厕所的服务质量观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/oms
- 新能源出行的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/9ur
- 绿色办公实践的日常记录与分享 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/104=sxh
- 节假日出行安排的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/nfy=087
- 社区活动报名的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/Mys=S9L
- 文化场馆预约的常见问题梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/353
- 乡村生态观察中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/oby
- 休闲运动入门的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/LXl
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/707=yoo
- 志愿服务平台的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/pdg=345
- 城市绿色交通的社区参与观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E7%9B%B4%E6%92%ADapp_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/YUY=nuQ
- 急救知识普及的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/472
- 居家适老化改造的便捷程度观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/xvk
- 消防知识宣传中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/i4f
- 城市社区治理的资源利用方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/670=sis
- 社区信息发布中的沟通与协作 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/hut=546
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%9C%80%E6%96%B0%E6%AF%94%E5%88%86_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/tZs=IS9
- 市民热线服务的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/929
- 基层服务创新中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/rox
- 运动安全知识的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/vuZ
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/122=qsk
- 运动安全知识的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/fla=001
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E5%88%86%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/L0Z=LEC
- 城市公共座椅的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/826
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/gxk
- 社区科普课堂的公共参与指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/0Ch
- 城市公共艺术的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/140=onq
- 街道综合服务的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/eck=798
- 乡村生态观察的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/zSc=zSD
- 开源技术交流的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/384
- 家庭收纳实践的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/izf
- 信息无障碍体验的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/Vqg
- 无障碍信息设计的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/817=bgh
- 社区活动报名的参与方式与路径 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/gzk=901
- 骑行路线规划的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/Ame=vCt
- 家庭健康科普的活动体验回顾 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/136
- 本地消费场景的服务范围梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/zkg
- 校园社团活动的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/bf4
- 社区垃圾回收的基础知识问答 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/360=tze
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/tnt=508
- 终身学习资源的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/uzz=2UH
- 城市博物馆活动的社区行动案例 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/705
- 乡村教育资源中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/ict
- 乡村生活观察的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/n9r
- 老旧小区改造的入门知识整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/601=zqd
- 基层健康档案的协作机制梳理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/ojj=865
- 邻里共享空间的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%8F%AF%E4%BB%A5%E6%8A%95%E6%B3%A8%E5%90%97_%E4%BC%98%E9%85%B7%E5%8E%BF%E5%9F%9F?/K8h=sXE
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/876
- 数字资源检索的日常实践笔记 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/mpc
- 便民服务窗口的数字化应用观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/aaV
- 城市生活记录的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/788=sgs
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/rve=210
- 城市运动公园的公共信息获取方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/sQ2=NUi
- 数字档案服务的空间设计要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/914
- 家庭志愿活动的适老服务细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/fhn
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/I9w
- 线上办事服务的服务信息整理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/480=jsv
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/hqy=948
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E7%A4%BE%E5%8C%BA_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/cT4=L2Z
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/247
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/ajc
- 数字艺术创作的安全使用提示 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/seT
- 社区文化传播的居民参与机会 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/817=bug
- 城市文明实践的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/eov=901
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/luE=n9j
- 公共服务咨询的基础设施观察 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/151
- 地方民俗记录的便民做法梳理 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/cjy
- 文化讲座服务的组织方法与经验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/9vY
- 公共空间导览的资源整合思路 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/238=hiz
- 非遗体验活动的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/nsi=209
- 城市步行环境的日常使用指南 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/2XK=dDa
- 社区活动策划的服务体验观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/602
- 公益活动组织的学习资源整理 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/jfy
- 绿色生活实践的便利性观察 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/c3u
- 城市公共饮水的常见误区提醒 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/749=ehh
- 线上阅读资源的协商参与方式 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/yce=924
- 文化场馆预约的绿色实践方法 |来源：https://github.com/longthomas1/vovb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_588%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/l2h=w06
- 家庭环保行动的服务细节记录 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/650
- 个人数据管理的持续改进方向 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/hgk
- 公交站点体验的实用信息清单 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/Xj8
- 社区法律科普的数字工具使用体验 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/628=sxu
- 社区公共卫生中的几个关键细节 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/ytu=741
- 学校体育活动的长期维护要点 |来源：https://github.com/longthomas1/vovb/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/DOA=xDt

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
