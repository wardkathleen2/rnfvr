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

- 数字支付体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%BA%AA%E5%AE%9E?/vpg=194
- 乡村生活观察中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%BA%AA%E5%AE%9E?/6RJ=sTC
- 信息无障碍体验的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/559
- 公交站点体验的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/moa
- 社区便民集市的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/sai
- 乡村文化活动的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/888=gfx
- 居家防滑改造的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/htj=586
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8818%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/kse=XLu
- 城市雨天出行的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/247
- 健康饮食教育的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/sed
- 生活垃圾回收的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/Oo6
- 乡村生活观察的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/616=spx
- 数字生活课堂的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/gne=211
- 职业技能学习的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/pFn=EWp
- 社区学习活动的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/677
- 家庭环保习惯的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/jek
- 数字支付体验的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/vjs
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/073=cux
- 老年友好服务中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/nsg=528
- 家庭运动计划的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/D9Z=VWV
- 应急物资管理的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/664
- 农业科普体验的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/wch
- 社区知识分享的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/hXA
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/880=iyi
- 农村环境治理的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/gjn=100
- 老年人文化生活的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8888cc%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/jzu=EfJ
- 社区活动策划的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/623
- 绿色生活实践的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/kop
- 本地旅行体验的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/fYX
- 数字公共文化的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/418=wcu
- 数字公共文化的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/bsj=594
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_8888cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/KAU=QaA
- 城市公共自行车的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/007
- 旧物循环利用的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/qyg
- 公共设施维护的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/mzN
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/964=qwb
- 家庭节能设备的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/iur=672
- 基层健康服务的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/TiQ=ErP
- 老年人文化生活的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/846
- 社区慢性病防控的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/huw
- 社区协商议事的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/YWl
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/497=krq
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/ipy=908
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/p4n=1IC
- 气象科普传播的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/821
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/iva
- 小区停车协商的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/1T8
- 城市骑行环境的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/201=jwf
- 青少年户外教育的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/xax=604
- 数字艺术创作的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/SI3=VuM
- 城市住房服务的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/107
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/knm
- 网络信息辨识的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/Vak
- 公共服务咨询的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/793=vip
- 终身学习资源的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/qcv=029
- 社区儿童活动的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_8888cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91066_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/5F2=I4c
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/156
- 街区更新实践的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/xxh
- 家庭饮食安排的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/2i8
- 社区安全巡查的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/406=bhf
- 城市适老服务的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/cnt=564
- 家庭环保行动的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8888cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/6Hk=iA0
- 社区心理支持的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/881
- 电子商务服务的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/day
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/zBy
- 城市树木认养的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/845=die
- 课后服务体验的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/nzs=975
- 健康信息获取的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_8G%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/qjG=J0f
- 城市雨天出行的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/600
- 开放数据应用的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/tgw
- 个人数据管理的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/YKj
- 城市农夫市集的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/990=imc
- 节假日出行安排的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/zwd=883
- 公园亲子设施的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_8g%E5%BD%A9%E7%A5%A8%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/pVq=tpH
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/579
- 城市噪声观察的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/auc
- 社区环保活动的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/qSY
- 城市公共艺术的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/219=ycj
- 乡村教育资源的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/llo=925
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_8G%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/fZy=oQA
- 城市公共厕所的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/489
- 社区科普课堂的协商参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/fad
- 节假日出行安排的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/ZiM
- 城市雨天出行的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/723=bwy
- 公共服务数字化的实用信息清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/itb=873
- 节约用水实践的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_8g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/EE1=qZ8
- 环境教育课程的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/468
- 老年数字阅读的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/kzx
- 社区菜市场服务的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/kyP
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/447=zup
- 健康饮食教育的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/gpv=607
- 城市文明实践中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_909%E6%B8%B8%E6%88%8F-%E6%9C%80%E5%A5%BD%E7%9A%84%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/Plu=rsS
- 科学信息获取的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/648
- 学校食育活动的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/rak
- 社区消防演练的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/Jk3
- 乡村生态观察的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/229=dzq
- 城市水环境观察的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/bac=113
- 地方戏曲体验的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/LGL=a5q
- 新能源知识普及的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/592
- 数字生活课堂的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/tpr
- 社区家政服务的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/DKc
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/694=ksi
- 社区文化节活动的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/vyc=116
- 乡村产业科普的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_909%E6%B8%B8%E6%88%8F%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/tb9=cxA
- 职业技能学习的服务范围梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/612
- 科学信息获取的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/puv
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/x4X
- 社区休闲设施的流程优化思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/078=wes
- 城市适老服务的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/pvz=172
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/xk6=prl
- 基层健康档案的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/939
- 安全出行教育的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/lhu
- 机器人科普活动的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/vnF
- 图书馆活动策划的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/639=udk
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/cas=695
- 租房信息服务的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/pjf=5he
- 城市文明出行的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/118
- 城市公共座椅的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/wcu
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/dXe
- 社区阅读服务的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/121=xkn
- 数字政务体验的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/dyi=772
- 城市慢行系统的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_9123welcome%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/eRm=kFk
- 家庭运动计划的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/575
- 儿童友好街区的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/hjl
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/S0t
- 社区安全巡查的学习资源整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/324=mzr
- 社区法律科普的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/aki=848
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_9123%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8_%E9%A1%BA%E4%B8%B0?/iRJ=mkh
- 社区便利生活的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/240
- 城市可持续生活的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/bki
- 社区托育服务的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/ffy
- 乡村休闲旅游的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/212=jyh
- 社区学习活动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/mpz=236
- 家庭收纳实践的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_9123%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/6iw=yF6
- 公共文化活动的社区行动案例 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/000
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/hbi
- 智能家居应用的活动组织技巧 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/Pjc
- 老年学习活动的数字化应用观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/235=ybi
- 城市噪声观察的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/bql=223
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_9123welcome%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/QqX=Sux
- 社区活动空间的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/681
- 亲子科普活动的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/khu
- 社区共享书架的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/S1B
- 文化讲座服务的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/504=oqk
- 本地消费场景的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/eyw=999
- 社区艺术活动的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Welcome9123%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/QJP=UfE
- 公交站点体验的便利性观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/079
- 智能手机助老的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/pfn
- 新能源出行的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/5Rp
- 小区公共照明的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/184=bmj
- 租房信息服务的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/xnb=919
- 本地历史资料的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%A8%E4%BB%80%E4%B9%88%E5%9C%B0%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/qi7=LQk
- 传统节日科普的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/383
- 社区知识分享的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/mgb
- 科学观察活动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/VXX
- 网络安全教育的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/939=gsm
- 城市基础设施的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/ujb=348
- 校园社团活动的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/ogW=x7B
- 网络信息辨识的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/043
- 家庭照护支持的活动体验回顾 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/dbr
- 基层服务创新的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/QFc
- 城市建设科普的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/596=sxw
- 社区邻里服务的常见误区提醒 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/yea=458
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_9123%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91welcome_36%E6%B0%AA%E7%9B%98%E7%82%B9?/6lM=Ikn
- 健康步道使用的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/755
- 城市公共座椅的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/tpl
- 家庭运动计划的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/v9q
- 科学信息获取的常见问题梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/669=vbi
- 城市公共自行车的服务质量观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/szg=415
- 社区养老服务的空间使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_967%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%B0%91%E7%94%9F?/dzp=aUr
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/911
- 社区商业活力的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/jpo
- 传统节日科普的适老服务细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/GQ2
- 乡村公共服务的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/880=esx
- 机器人科普活动中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/eok=492
- 社区托育服务的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_967%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/0aQ=VfD
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/980
- 休闲运动入门的日常记录与分享 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/ish
- 食品安全科普的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/GhQ
- 社区快递服务的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/180=wae
- 社区花园共建的基础设施观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/joe=888
- 志愿服务平台的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_967%E5%BD%A9%E7%A5%A8967CC_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/u9Y=DDI
- 社区休闲设施的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/362
- 社区垃圾分类的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/hgd
- 本地历史资料的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/hNY
- 城市展览体验的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/400=suf
- 基层健康服务的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/twm=564
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_967%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%85%A8%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/UlF=tpB
- 机器学习入门的资源利用方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/680
- 社区商业活力的协作机制梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/std
- 社区安全巡查的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/ZuJ
- 运动安全知识的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/354=nxo
- 创业经验分享的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/urf=149
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/s3A=O5E
- 数字支付体验的基础知识问答 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/554
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/zjd
- 公共场所导视的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/BV3
- 数字创作工具的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/446=pgf
- 文化讲座服务的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/isg=781
- 乡村产业科普的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/yef=GTA
- 小区停车协商的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/068
- 小区停车协商的日常实践笔记 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/mvq
- 地方戏曲体验的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/VlW
- 社区活动空间的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/194=don
- 科学信息获取的空间设计要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/ura=194
- 老年智能设备的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_967%E5%8D%9A%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/F53=8KF
- 城市文化路线的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/459
- 数字学习资源的入门知识整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/ffk
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/VC9
- 青年职业探索的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/972=stk
- 文明养宠科普的绿色实践方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/tno=670
- 公交无障碍服务的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/9rb=1en
- 数字支付体验的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/458
- 图书馆数字服务的资源整合思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/yer
- 城市体育设施的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/VjX
- 社区消防演练的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/037=eta
- 科学观察活动中的沟通与协作 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/gnt=628
- 社区手工活动的组织方法与经验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_9797%E5%BD%A9%E7%A5%A8App_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/eoK=wMI
- 文化场馆预约的实际需求与回应 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/885
- 城市文明出行的参与方式与路径 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/yuf
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/wZM
- 节约用水实践的日常使用指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/866=pwi
- 家庭教育交流的执行流程参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/hve=239
- 小区停车协商的行动步骤参考 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9797.cn%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/TNb=dD7
- 社区知识分享的活动策划思路 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/930
- 街区道路维护的居民参与机会 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/euo
- 创业经验分享的儿童友好细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/lqc
- 公共空间导览的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/566=mkm
- 网络信息辨识的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/rxs=239
- 线上办事服务的持续改进方向 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/k4e=fuS
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/139
- 家庭理财科普的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/lct
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/SRY
- 个人时间管理的日常管理方法 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/719=qhs
- 绿色快递包装的设施维护观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/jtf=101
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_9797.%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0?/T8B=S59
- 通勤路线规划的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/116
- 智慧停车服务的公共参与指南 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/oow
- 社区共享书架的长期维护要点 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/7X9
- 家庭健康管理的安全使用提示 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/908=cwr
- 日常摄影记录中的几个关键细节 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/sfh=877
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/gordoncarol8/ofvm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_9797cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A8%E9%9D%A2%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/DKQ=sO4
- 读书会组织从使用体验看服务改进 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/926
- 节能生活方式的便捷程度观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/vtk
- 老年人出行服务的服务信息整理 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/Mds
- 无障碍出行的社区参与观察 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/498=euh
- 公共空间休憩的家庭实践清单 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/cdt=080
- 生活垃圾减量的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_9797%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/mTz=oiX
- 校园阅读活动的服务细节记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/188
- 城市可持续生活的线下体验记录 |来源：https://github.com/gordoncarol8/ofvm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/lai

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
