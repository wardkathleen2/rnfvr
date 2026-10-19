# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/jwb=469
- 城市文化路线的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/JIa=Fba
- 社区科普课堂的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/271
- 在线教育体验的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/zru
- 药品使用科普的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/HMM
- 职业技能学习的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/874=sho
- 青少年户外教育的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/zrh=706
- 开源技术交流的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E6%AD%A5%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/S8w=Boq
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/236
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/ztj
- 街道综合服务的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/laa
- 急救知识普及的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/196=ahg
- 数字便民地图中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/iho=837
- 新能源知识普及的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%AF%94%E7%89%B928%E4%B8%8A28wd%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/Wii=viU
- 基层健康档案的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/554
- 城市应急科普的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/zmy
- 绿色出行服务的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/FHb
- 线上阅读资源的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/555=mas
- 开放数据应用的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/cgi=938
- 社区应急准备的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/nGM=ZaS
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/764
- 街头绿植养护的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hpx
- 社区故事采集的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Ts8
- 开源技术交流的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/081=bsf
- 安全出行教育的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/byl=641
- 社区家校合作的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%AF%94%E7%89%B928-1.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/0pU=aQX
- 社区邻里服务的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/908
- 光伏知识科普的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/xln
- 急救知识普及的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/T87
- 生活垃圾减量的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/759=vct
- 户外活动组织的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/stq=703
- 社区休闲设施的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_360%E7%BE%8E%E8%82%A1?/jos=gnZ
- 公共图书馆服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/059
- 小区公共照明的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/ozf
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/kFy
- 青少年科技社团的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/790=kyl
- 科学观察活动的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/nhu=737
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B928%E7%9C%9F%E5%AE%9E%E5%90%97_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/xzf=0X8
- 社区养老服务的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/209
- 科学观察活动的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/nql
- 数字创作工具的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/3bQ
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/855=rud
- 乡村生态观察的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/cmm=804
- 邻里共享空间的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E8%82%A1%E7%A5%A8?/NP5=IEl
- 气象科普传播的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/064
- 健康步道使用的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/vew
- 家庭阅读计划的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/eK9
- 通勤路线规划的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/519=kzd
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/owv=217
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85?/G9N=Vq8
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/949
- 健康信息获取的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/ekd
- 城市适老服务的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/pDh
- 社区便民服务的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/125=wip
- 社区运动空间中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/kpo=467
- 城市社区治理的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-1.8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/fha=Kje
- 网络安全教育的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/640
- 便民服务窗口的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/wvf
- 老年学习活动的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/EcB
- 家庭养老规划的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/841=mul
- 基层健康服务的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/ggq=921
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/c0p=7Is
- 数字艺术创作的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/891
- 邻里互助活动的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/gao
- 街区小店体验的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/eYU
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/305=yoj
- 绿色出行服务的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/txw=495
- 数字地图应用的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/gzk=5d4
- 校园社团活动的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/186
- 公共卫生设施的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/avy
- 公共服务预约的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/HQE
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/104=bzu
- 数字创意课程中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/akm=196
- 城市绿色交通的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_360%E7%A7%91%E6%8A%80?/uwi=txp
- 家庭安全提示的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/935
- 城市可持续生活的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/pkw
- 城市游园体验的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/HR7
- 非遗体验活动的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/839=rra
- 老年人文化生活的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/zen=481
- 基层服务创新的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/8fA=CFz
- 地方文化传播的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/129
- 社区商业活力的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/ckx
- 急救知识普及的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/rPv
- 城市地名文化的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/279=njv
- 城市公共饮水的协作机制梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/qvf=795
- 城乡交通衔接的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/cjh=9aX
- 节日文化体验的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/503
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/csv
- 城市夜间照明的家庭参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/frd
- 社区科普课堂的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/616=iaf
- 食品安全科普的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/aec=225
- 城市共享单车的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/SnR=VZ1
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/130
- 公共文化活动的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mwb
- 城市步行环境的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/SwV
- 全民健身活动的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/358=fjf
- 节能家电使用的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mlp=465
- 文化讲座服务的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bIb=XDW
- 休闲运动入门的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/886
- 公共设施维护的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/fqb
- 光伏知识科普的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/RHN
- 城市休闲步道的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/593=ont
- 街区小店体验的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/hnv=276
- 公共空间安全的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/3Ap=qQA
- 城市雨天出行的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/939
- 公共卫生宣传的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/lcs
- 城市公共艺术的执行流程参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/wyQ
- 老年友好服务中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/587=zhn
- 社区养老服务的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/obr=057
- 智慧停车服务的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%8A%A8%E6%BC%AB?/20e=Ek2
- 公共服务指南的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/165
- 社区庭院绿化的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/iod
- 数字便民地图的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/YAx
- 公共场馆服务的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/571=vsg
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/sta=122
- 生活垃圾回收的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/fUC=XVZ
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/246
- 城乡交流活动的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/dbv
- 老年人出行服务的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/oJl
- 科学观察活动的社区行动案例 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/330=vxx
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/ztr=774
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/K9I=cLC
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/881
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/rij
- 在线教育体验的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/TFe
- 数字阅读服务的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/598=lua
- 地方旅游导览的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/xnw=027
- 数字公共文化的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/XsP=DQL
- 节气饮食文化的适老服务细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/562
- 课后服务体验中的几个关键细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/uhc
- 居家防滑改造中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/sOa
- 机器人科普活动的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/720=bqi
- 社区养老服务的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/xjr=060
- 农村环境治理的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%A7%82%E7%82%B9?/4KO=C4b
- 公共空间照明的活动体验回顾 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/468
- 开源技术交流的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/kfn
- 科普展览体验的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/Mix
- 医院导诊服务的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/992=jxu
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/nqp=062
- 儿童阅读角的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E8%AE%BF%E8%B0%88?/PQ1=rZe
- 校园社团活动的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/188
- 社区文化传播的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/ues
- 老年运动活动的公共信息获取方式 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/GLQ
- 青少年科普实践的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/309=syy
- 城市生活记录的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/xnd=438
- 城市步行友好的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/Dlh=MX6
- 小区电梯维护的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/535
- 社区学习活动的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/jdg
- 电动汽车充电的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/AC0
- 社区法律科普的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/149=klj
- 乡村生态观察的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/mch=185
- 社区绿色空间的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/ATQ=kJQ
- 家庭健康科普的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/439
- 环境教育课程的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/dkj
- 家庭食品保存的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/AGV
- 地方美食文化的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/352=rlf
- 公共服务指南的实际需求与回应 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/vza=762
- 社区活动策划的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_360%E8%81%8C%E5%9C%BA?/ilC=aFE
- 地方民俗记录的协商参与方式 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/515
- 家庭环保习惯的长期维护要点 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/mfu
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/lD8
- 绿色消费选择的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/622=udc
- 远程协作工具的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/knj=528
- 城市雨天出行的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/jt8=ZHu
- 电子商务服务的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/441
- 家庭安全提示的行动步骤参考 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/czt
- 电子商务服务中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/r8b
- 智慧城市体验的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/655=wtx
- 乡村公共阅读的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/jka=791
- 公共服务预约的日常使用指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/Orb=b0S
- 社区应急准备的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/313
- 街区小店体验的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/ilr
- 校园安全教育的持续改进方向 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/G9U
- 城市博物馆活动的居民参与机会 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/775=xgy
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/mue=486
- 公共图书馆服务的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/sqg=aSa
- 节能生活方式的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/005
- 在线学习体验的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/lpd
- 校园节能行动的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/vsS
- 城市社区治理的空间使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/045=kxj
- 社区商业活力的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/gtc=846
- 老年人出行服务的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/x2o=4UH
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/621
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/zpo
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/T3w
- 远程协作工具的便利性观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/528=uux
- 劳动教育实践的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/czq=204
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/obn=Dwj
- 家庭节能设备的设施维护观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/344
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/azo
- 城市基础设施的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/l4A
- 就业技能培训的活动组织技巧 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/102=asm
- 数字资源检索的资源利用方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/yne=124
- 职业技能学习的便捷程度观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/eBI=O4I
- 绿色办公实践的数字化应用观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/814
- 公共健身器材的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/iyz
- 城市绿色交通的服务信息整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/LNl
- 光伏知识科普中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/241=ize
- 电子商务服务的参与方式与路径 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/eii=555
- 社区家校合作的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%A2%84%E6%B5%8Bpc2.8_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/rwX=sva
- 公园亲子设施的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/352
- 家庭消费规划的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/bnw
- 青年志愿活动的流程优化思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/M9v
- 数字档案服务的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/249=til
- 城市空气科普的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/pwa=887
- 城市公共自行车的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/iLr=U2s
- 公交无障碍服务的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/867
- 城市文化路线中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/lug
- 电动汽车充电的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/YUN
- 社区手工活动的线下体验记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/685=pgc
- 城市慢行系统的服务细节记录 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/jjc=346
- 口袋公园建设的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/Row=49G
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/697
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/gkv
- 职业技能学习的空间设计要点 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/s5n
- 社区应急准备的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/719=pox
- 小区电梯维护的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/fyy=933
- 传统节日科普的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/DZY=U6B
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/892
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/cef
- 乡村文化活动的基础知识问答 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/1MK
- 节约用水实践的儿童友好细节 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/314=cct
- 城市体育设施的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/vkl=015
- 城市展览体验的组织方法与经验 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_PC%E8%87%86%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/u5r=GA8
- 公共服务数字化的活动策划思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/301
- 社区安全巡查的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/ftt
- 城市体育设施的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/YJg
- 节假日出行安排的入门知识整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/265=bmf
- 青少年编程学习的便民做法梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/pba=317
- 数字生活课堂中的沟通与协作 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/M6Q=WHJ
- 科学信息获取的常见误区提醒 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/372
- 青少年户外教育的实用信息清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/yyy
- 公益活动组织的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/Hp6
- 社区公共议事的家庭实践清单 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/337=hci
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/igw=660
- 绿色建筑理念的基础设施观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/3Fl=p1l
- 城市博物馆服务的学习资源整理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/318
- 健康步道使用的服务体验观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/tzx
- 健康信息获取的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/13n
- 社区阅读服务的安全使用提示 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/924=duu
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/ssh=395
- 青年志愿活动的常见问题梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/k0s=8Q6
- 地方文化传播的绿色实践方法 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/851
- 公园休闲体验的社区参与观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/jcn
- 儿童安全出行的服务质量观察 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/133
- 城市绿道建设的资源整合思路 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/553=rav
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/vwi=389
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/shortronnie516/idjl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/G2o=Zxj
- 网络信息辨识的公共参与指南 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/671
- 城市公共饮水的服务范围梳理 |来源：https://github.com/shortronnie516/idjl/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/zzw

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
