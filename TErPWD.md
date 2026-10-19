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

- 城市住房服务中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/216
- 城市噪声观察的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/bnv
- 垃圾分类指导的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/ndC
- 新能源出行的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/169=fji
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/axn=716
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_app%E8%87%AA%E5%8A%A9%E9%A2%86%E5%8F%96%E5%BD%A9%E9%87%91128%E5%85%83_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/ICm=Scc
- 公共设施使用的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/834
- 城乡交流活动的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/rro
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/Abw
- 城市可持续生活的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/977=hdo
- 物业服务沟通的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/wzo=711
- 课后服务体验的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_welcome%E5%BD%A9%E5%AE%9D%E8%B4%9D%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/GAD=VGD
- 科学信息获取的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/403
- 街区更新实践的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/ajy
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/Rky
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/971=lrc
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/ubx=566
- 图书借阅体验的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/WZI=OFl
- 数字创意课程的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/356
- 儿童运动体验中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/srp
- 小区电梯维护的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/JY4
- 社区便民集市的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/062=cju
- 城市博物馆服务的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/roj=729
- 地方戏曲体验的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/PN5=bsC
- 家庭照护支持的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/262
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/qqe
- 街区道路维护的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/qwK
- 小区停车协商的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/858=huk
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/uwy=759
- 非遗课堂体验的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/HMa=2DC
- 农业科普体验的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/616
- 应急物资管理的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/wkr
- 城市地名文化的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/OXk
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/604=xvv
- 社区托育服务的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/tmq=489
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BC%9A%E5%91%98_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/yAP=w8v
- 社区体育组织的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/277
- 绿色出行服务的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/suy
- 职业技能学习的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/42k
- 亲子阅读活动的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/826=zhu
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/dbp=581
- 科普展览体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/DCR=UUJ
- 环境监测科普的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/258
- 社区邻里服务的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/rrs
- 社区休闲设施的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/G6z
- 城市共享单车的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/595=pfp
- 软件开发学习的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/wdx=443
- 社区艺术活动的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/6xj=8lY
- 城市步行环境的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/073
- 学校体育活动的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/qtz
- 城市农夫市集的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/eRw
- 在线教育体验的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/798=pkm
- 物业服务沟通的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/fmx=521
- 数字支付体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E4%B8%93%E5%AE%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/Bow=a49
- 基层健康服务的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/701
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/pjn
- 青年志愿活动的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/dsr
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/097=wmw
- 科学教育活动的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/anl=923
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%85%A8%E5%A4%A9%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/0IY=Wnw
- 城乡公共服务的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/766
- 青少年科普实践的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/hhd
- 社区托育服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/2Ea
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/939=dlk
- 软件开发学习的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/iuz=547
- 公共空间导览的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/c90=n0s
- 城市水环境观察的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/606
- 公交站点体验的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/yra
- 信息无障碍体验的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/3ng
- 绿色校园实践的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/452=jwu
- 本地消费场景的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/kqz=210
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92q%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/14S=5mt
- 社区休闲设施的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/492
- 社区共享书架的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/jcm
- 公共卫生设施的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/eqd
- 乡村教育资源的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/295=qru
- 节能家电使用的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/bun=511
- 城市绿色交通的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/gDE=ASR
- 数字创意课程的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/481
- 健康饮食教育的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/pqk
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/FJf
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/701=yak
- 绿色校园实践的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/ydx=566
- 农村环境治理的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/4ih=hXA
- 青少年编程学习中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/243
- 社区志愿服务的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/bdy
- 城市文化路线的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/WTc
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/339=xpv
- 儿童运动体验的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/doi=860
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/u8G=RCW
- 社区教育资源的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/235
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/jhg
- 周末休闲规划的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/ALp
- 城市可持续生活的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/748=blo
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/prt=389
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E6%9C%AC%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/Xmt=OVl
- 文明养宠科普的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/839
- 街头绿植养护的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/bpm
- 社区养老服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/yF4
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/687=ckv
- 数字公共文化的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/rye=602
- 智能家居应用的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E9%AB%98%E6%89%8D%E9%80%9A%E8%AE%A1%E5%88%92-%E9%A6%99%E6%B8%AF_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/4AL=veN
- 乡村教育资源的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/178
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/ogu
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/GPY
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/388=bje
- 地方民俗记录的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/eoa=595
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B6%85%E7%BA%A7%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/Kxm=ngn
- 老年学习活动的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/313
- 社区慢性病防控的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/myp
- 科技馆参观体验的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/E6E
- 老旧小区改造的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/992=loe
- 校园安全教育的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/ful=521
- 志愿服务平台的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/cOZ=sXe
- 社区便民服务的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/311
- 科技馆参观体验的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/yjf
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/740
- 校园社团活动的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/222=jys
- 传统节日科普的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/iqy=514
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/e92=WIl
- 地方民俗记录的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/397
- 环境监测科普的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/zpr
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/Emg
- 老年人日常照护的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/090=lxv
- 家庭食品保存的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/vpq=968
- 个人时间管理的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E9%87%91%E7%89%8C%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/5Am=vMa
- 社区宠物管理的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/309
- 生活技能分享的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/klc
- 节假日出行安排的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/JnR
- 线上办事服务的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/205=hsj
- 城市绿色交通中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/nvf=608
- 户外活动组织中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/MPd=rHI
- 社区艺术活动的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/854
- 社区共享书架的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/ity
- 公园亲子设施中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/nXp
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/267=eay
- 青少年心理健康的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/zka=365
- 街道综合服务的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88q_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/69s=TRV
- 城市运动公园的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/171
- 社区阅读服务的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/uap
- 生活服务数字化的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/J6l
- 儿童户外活动的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/486=fds
- 图书借阅体验的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/lun=561
- 安全出行教育的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%844%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/EPu=u7j
- 旧物循环利用的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/602
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/qqr
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/c4Y
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/295=yum
- 个人信息保护的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/ooo=318
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/SmE=VZd
- 地方美食文化的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/792
- 社区法律科普的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/zyp
- 节日文化体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/VLT
- 职业技能学习的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/616=wof
- 健康信息获取的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/uqo=728
- 公共图书馆服务的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/cNb=aRO
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/421
- 儿童安全出行的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/jjf
- 城市展览体验的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/OxQ
- 公园亲子设施的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/797=pqk
- 读书会组织的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/fcq=489
- 社区宠物管理的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%BB%E7%AB%99_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/Aoz=Ohy
- 周末休闲规划的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/145
- 学校食育活动的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/osu
- 家庭志愿活动的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/UvZ
- 绿色办公实践的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/061=exx
- 光伏知识科普中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/pir=052
- 家庭健康管理的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/0lr=iKz
- 本地旅行体验的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/287
- 家庭教育交流的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/tpt
- 街区小店体验的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/evQ
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/624=srv
- 基层服务创新的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/uaw=662
- 社区活动空间的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/cdh=tt9
- 口袋公园建设的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/944
- 便民信息查询的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/lco
- 骑行路线规划的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/NkF
- 社区养老服务的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/739=euh
- 社区手工活动的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/tji=778
- 社区应急准备的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/3ZJ=Ssl
- 城市骑行环境的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/083
- 食品安全科普的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/wrs
- 数字阅读服务的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/cAF
- 家庭运动计划的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/931=vsn
- 远程协作工具的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/lfy=781
- 社区体育组织的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/BGj=8DG
- 乡村电商实践的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/033
- 乡村公共阅读的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/pnq
- 社区教育资源的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/xlf
- 科技馆参观体验的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/982=mlm
- 社区交通安全的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/qnj=956
- 农村环境治理的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/2gS=C4I
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/672
- 公园无障碍服务的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/deo
- 生活垃圾减量的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/Ags
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/534=xqt
- 社区法律科普的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/tbb=913
- 运动安全知识的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/YkM=OxA
- 社区志愿服务的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/385
- 乡村文化活动的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/kti
- 街区道路维护的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/yq5
- 公共服务咨询的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/188=lmh
- 家庭教育交流的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/khn=900
- 老年学习活动的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_24%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_36%E6%B0%AA%E4%BF%A1%E6%89%98?/pPj=DN9
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/616
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/wvh
- 节约用水实践的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/cCo
- 社区教育资源的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/395=qum
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/ovl=059
- 智能家居应用的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_36%E6%B0%AA%E5%88%9B%E6%8A%95?/pXZ=PMp
- 家庭消费规划的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/711
- 社区托育服务的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/sen
- 城市公共标识的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/GI5
- 数字创意课程的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/620=ulx
- 终身学习资源的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/dul=201
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/yx4=eDP
- 本地历史资料的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/519
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/nih
- 乡村公共服务的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/AAN
- 数字生活课堂的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/184=tgz
- 节假日出行安排的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/fxw=770
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/B4a=53s
- 城市慢行系统的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/205
- 数字公共文化的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/owo
- 居民健康教育的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/Rxh
- 居民健康教育中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/878=tqa
- 数字生活课堂的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/jjy=780
- 节气饮食文化的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/nfj=Ujs
- 公共交通接驳的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/579
- 急救知识普及的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/uga
- 网络安全教育中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/Jye
- 便民服务窗口的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/022=jcj
- 城市适老服务的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/jcz=695
- 公共文化活动的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/Ccj=dGI
- 市民热线服务的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/038
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/boy
- 社区庭院绿化的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/jWR
- 无障碍信息设计的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/371=ejl
- 志愿者培训交流的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/lyb=566
- 环境教育课程的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/eVG=VS1
- 老年友好服务的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/979
- 绿色快递包装的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/efd
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/A0e
- 个人数据管理的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/510=exc
- 生活服务数字化的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/afh=628
- 学校食育活动中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/ZNr=qYZ
- 基层健康档案的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/118
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/ndu
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/7EE
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/507=kmu

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
