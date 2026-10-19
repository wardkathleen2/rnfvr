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

- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/La9
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/601=yts
- 物业服务沟通的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/ljd=832
- 非遗体验活动的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/8pK=oel
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/618
- 城市运动公园的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/lzx
- 家庭环保行动的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/lb0
- 基层健康档案的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/769=xjd
- 开源技术交流的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/kka=105
- 街道综合服务的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/xy3=9Jy
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/817
- 绿色校园实践的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/kbt
- 城市住房服务的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/v8V
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/824=vos
- 公共交通接驳中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/evf=565
- 家庭饮食安排的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_6G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/Fu7=mbT
- 乡村产业科普的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/249
- 在线教育体验的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/xwy
- 社区菜市场服务的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/En0
- 乡村生活观察的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/748=lad
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/xql=840
- 学校体育活动的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/0rD=8av
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/483
- 数字艺术创作的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/lpr
- 乡村教育资源的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/gbS
- 社区便民集市的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/518=ala
- 家庭网络使用的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/omp=138
- 本地旅行体验的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_6G%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/2Ic=xnz
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/596
- 城市公共厕所的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/jrp
- 课后服务体验的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/bEG
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/903=cub
- 科学运动指导的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/wsj=009
- 公共设施使用的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/1zc=rLY
- 医院导诊服务的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/113
- 科学教育活动的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/qga
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/DXT
- 人工智能科普的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/438=aur
- 社区共享书架的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/ygy=094
- 无障碍出行的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/Ali=pCW
- 低碳社区实践的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/541
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/ajd
- 城市生活记录的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/vYr
- 儿童安全出行中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/810=bee
- 智能手机助老的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/yqq=545
- 校园社团活动的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_6G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/vSk=qIZ
- 社区宠物管理的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/571
- 家庭照护支持的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/nxe
- 科学信息获取的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/JXu
- 家庭志愿活动的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/689=tcj
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xef=065
- 社区商业活力的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_6G%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6Id=ZfP
- 城市文化路线的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/520
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/tvm
- 社区协商议事的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/Yu2
- 公交站点体验的活动组织技巧 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/856=ido
- 公共空间照明的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/zfr=429
- 乡村教育资源的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_6G%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/AOO=wll
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/027
- 城市步行友好的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/wec
- 市民热线服务的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/gqc
- 城市社区治理的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/133=jxf
- 家庭运动计划的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/ejx=152
- 家庭安全提示的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_6G%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/lPw=S1w
- 社区便利生活的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/933
- 租房信息服务的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/ggj
- 城市公共标识的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/PIl
- 城市夜间照明的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/455=cec
- 电动汽车充电的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/dhs=398
- 儿童安全出行的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/aE7=t9n
- 线上办事服务的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/009
- 街区更新实践的安全使用提示 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/lmu
- 安全出行教育的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/Btv
- 公园无障碍服务的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/680=exu
- 无障碍出行的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/fie=461
- 社区慢性病防控的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_6G%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/ZlK=76B
- 社区消防演练的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/279
- 社区公共卫生的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/gxy
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/Z5X
- 公共场所导视的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/326=nbr
- 在线教育体验的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/ptj=600
- 老年数字阅读中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_6G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/kL2=coM
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/791
- 数字创意课程的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/kqv
- 社区宣传栏更新的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/nUZ
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/705=uxd
- 食品配送体验的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/god=369
- 社区家政服务的常见问题梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/c2U=iFO
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/689
- 社区家校合作的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/ayk
- 街区绿化养护的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/0lt
- 城市骑行环境的活动策划思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/573=exn
- 青少年科普实践的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/eub=140
- 绿色办公实践的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/J09=hSn
- 科学观察活动的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/948
- 租房信息服务的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/vbp
- 城市基础设施的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/Rs1
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/724=kfv
- 消防知识宣传的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/bft=309
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/JI2=wQW
- 老年学习活动的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/953
- 老年运动活动的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/qry
- 公交站点体验的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/6yy
- 校园阅读活动的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/988=vve
- 公共空间照明的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/nvm=640
- 地方旅游导览的线下体验记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/Uyi=muf
- 安全出行教育的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/688
- 基层服务创新的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/gut
- 在线教育体验的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/LaW
- 城市便民驿站的服务细节记录 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/999=pwk
- 社区学习活动的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/fyf=544
- 职业技能学习的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/6gB=2wt
- 居家防滑改造的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/866
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/fqq
- 邻里互助活动的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/SBo
- 社区故事采集的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/770=kzz
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/cbs=331
- 社区环保活动的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/k2F=6Ve
- 创业经验分享的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/578
- 数据分析入门的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/xtm
- 生活服务数字化的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/3vE
- 青少年科普实践中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/378=zme
- 家庭环保行动的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/kor=527
- 社区学习活动的便民做法梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/urc=39E
- 数字设备回收的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/248
- 公共场馆服务的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/ehf
- 校园安全教育的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/DTo
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/260=yey
- 科普展览体验的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/dya=443
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/pic=p5F
- 乡村生态旅游的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/600
- 社区文化节活动的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/jxe
- 社区信息发布的长期维护要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/zVF
- 社区公共议事的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/229=mxu
- 小区停车协商的便利性观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/ras=922
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/OnZ=RCZ
- 公共空间休憩的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/606
- 软件开发学习的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/fvw
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/5vX
- 城市噪声观察的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/405=pol
- 日常摄影记录的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/oyo=873
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/FwO=rvD
- 社区生活指南的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/912
- 社区修缮行动的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/jxk
- 人工智能科普的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/S7i
- 校园节能行动的儿童友好细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/009=bhw
- 社区教育资源的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/dau=171
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/j8X=c1M
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/477
- 绿色办公实践的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/bxc
- 健康饮食教育的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/rUW
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/221=lbn
- 网络安全教育的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/vsr=772
- 公共设施使用的基础设施观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/UJF=LoW
- 青年就业服务的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/782
- 物业服务沟通的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/esr
- 儿童安全出行的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/QBb
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/944=zrq
- 社区体育组织的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/xgi=626
- 非遗课堂体验的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/P64=Zb7
- 城市文明实践的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/710
- 开放数据应用的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/qay
- 无障碍出行的持续改进方向 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/1MV
- 城市可持续生活的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/562=buh
- 社区老年食堂的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/etz=664
- 社区阅读服务的参与方式与路径 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/R3d=Rdz
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/663
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/hwo
- 图书借阅体验的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/Vzt
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/778=wzv
- 灵活就业交流的日常记录与分享 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/vkr=452
- 数字设备回收的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/8Gl=LdZ
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/389
- 城市共享单车的流程优化思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/plu
- 数字课堂应用的适老服务细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/B4d
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/262=ave
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/lif=117
- 城市绿色交通中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/wBr=JKh
- 本地消费场景的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/209
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/wkr
- 城市公共艺术的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/BOk
- 公共设施使用的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/196=gxf
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/ppa=384
- 智慧停车服务的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/QA9=biF
- 社区交通安全的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/057
- 城市住房服务的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/hgf
- 生活垃圾减量的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/q4a
- 乡村公共服务的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/439=gct
- 公园休闲体验的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/ehv=419
- 急救知识普及的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/GOt=ORq
- 家庭健康科普的常见误区提醒 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/851
- 公共卫生宣传的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/fep
- 社区邻里服务的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/nlr
- 日常摄影记录中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/263=fjz
- 传统节日科普的空间设计要点 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/tqx=713
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/xav=Mv8
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/145
- 绿色消费选择的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/lkw
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/0MJ
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/047=rom
- 市民意见收集的社区行动案例 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/jpi=690
- 乡村阅读空间的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/xXX=Taj
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/293
- 无障碍信息设计的居民参与机会 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/cyd
- 家庭节能实践的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/6sP
- 社区互助网络的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/036=qmn
- 非遗课堂体验的基础知识问答 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/ioi=634
- 城市住房服务的设施维护观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_767cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/2EZ=qri
- 环境教育课程的服务质量观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/641
- 校园安全教育的学习资源整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/qlk
- 乡村教育资源的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/om6
- 志愿服务平台的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/276=yla
- 本地消费场景的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/glq=864
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/VJh=QxG
- 网络安全教育中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/384
- 公共空间照明的空间使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/bsp
- 安全出行教育的组织方法与经验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/Kmi
- 社区休闲设施的日常管理方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/131=eyd
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/yro=416
- 线上办事服务的服务反馈渠道 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/h1u=VA8
- 社区公共卫生的社区参与观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/271
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/tpg
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/3wd
- 社区活动报名的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/416=yyh
- 社区养老服务的数字化应用观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/iqy=161
- 街区道路维护中的沟通与协作 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/OY5=ykl
- 公共场所导视的入门知识整理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/055
- 社区修缮行动的协商参与方式 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/azv
- 社区学习活动的活动体验回顾 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/VeP
- 线上办事服务的便捷程度观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/204=rol
- 社区共享书架的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/fnh=388
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/L3b=Htf
- 老年友好服务的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/135
- 个人时间管理的阅读与学习资源 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/gue
- 节气饮食文化的执行流程参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/Qu3
- 老年运动活动的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/300=eyg
- 科学信息获取的行动步骤参考 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/ltg=636
- 社区花园共建的服务体验观察 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/qyT=A1K
- 乡村文化活动的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/810
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/qma
- 开放数据应用的家庭实践清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/29T
- 公共服务数字化的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/851=lvg
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/ebq=298
- 城市夜间照明的日常实践笔记 |来源：https://github.com/moralesbenjamin09/ared/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/ukd=TXd
- 城市公共座椅的绿色实践方法 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/597
- 公共服务沟通的实用信息清单 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/wwc
- 社区学习活动的协作机制梳理 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/MbH
- 家庭节能设备的日常使用指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/436=gum
- 城市应急广播的资源整合思路 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/khe=110
- 城市噪声观察的公共参与指南 |来源：https://github.com/moralesbenjamin09/ared/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E8%BD%AC%E8%BD%BD?/DFE=2WE

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
