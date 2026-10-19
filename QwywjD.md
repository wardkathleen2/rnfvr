# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:23**

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

- 公共服务沟通的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/AdW
- 城市便民驿站的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/943=bdg
- 周末休闲规划的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/clz=595
- 数字资源检索的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/yR3=Vfn
- 城市农夫市集的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/293
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cyu
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/3lH
- 乡村文化空间的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/270=qgp
- 乡村生态观察的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ppp=512
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/zY1=zo1
- 社区健康讲座的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/709
- 社区家校合作的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/csd
- 骑行路线规划的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/kZb
- 乡村阅读空间的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/478=ias
- 社区商业活力的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/hdb=871
- 绿色消费选择的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/kvr=OSW
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/766
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/sci
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/qXA
- 老年数字阅读的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/476=psu
- 骑行路线规划的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/bsj=423
- 线上阅读资源的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/QqS=y8O
- 远程协作工具的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/657
- 绿色消费选择的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/sxh
- 节气饮食文化的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/7aG
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/418=oze
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/hbx=606
- 社区知识分享的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/0dg=gXe
- 街头绿植养护的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/884
- 老年人出行服务的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/koa
- 社区文化传播的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/uS8
- 线上办事服务的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/580=syc
- 科学运动指导的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/wmz=622
- 家庭饮食安排的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/VeI=r14
- 社区故事采集的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/570
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/jdw
- 电动汽车充电的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/Iun
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/615=tlh
- 数字便民地图的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/uja=474
- 社会体育指导的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/k48=RQN
- 社区休闲设施中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/626
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/iqc
- 社区便利生活的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/VQr
- 智慧停车服务的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/951=nuz
- 公共图书馆服务的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/sxi=603
- 街区更新实践的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/3vX=qhO
- 数字创作工具的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/668
- 青少年科普实践的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/gzb
- 图书借阅体验的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/tfS
- 社区公共餐饮的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/072=ehn
- 环境监测科普的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/txf=212
- 低碳社区实践的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/DKi=6zj
- 本地旅行体验的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/457
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/thx
- 社区养老服务的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/DCX
- 乡村阅读空间的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/225=zmd
- 家庭理财科普的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/szj=023
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/gTN=f5f
- 城市微更新实践的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/324
- 新能源出行的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/jhv
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/qoy
- 绿色生活实践的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/905=azm
- 地方美食文化的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/cri=015
- 社区绿色空间的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/fCN=osE
- 乡村公共文化的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/548
- 科学观察活动的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/mun
- 就业技能培训的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/Xs3
- 社区信息发布的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/319=zew
- 青少年户外教育的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/ikq=582
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/6wd=d3b
- 绿色出行服务的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/307
- 社区阅读服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/acm
- 家庭运动计划的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/RBj
- 社区托育服务的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/048=rid
- 街区道路维护中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/wrs=668
- 智慧城市体验的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9A%E4%BF%A1?/C3N=BHC
- 健康饮食教育的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/954
- 城市应急广播的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/tdy
- 地方民俗记录的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/rzn
- 家庭理财科普的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/683=zxy
- 儿童安全出行的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/ale=805
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/A4p=dua
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/244
- 在线教育体验的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/kpo
- 数字公共文化的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/Ti5
- 社区活动报名的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/371=hco
- 城市体育设施的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/lba=498
- 健康饮水科普的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%88%B7%E5%A4%96?/zhg=kEo
- 光伏知识科普的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/626
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/dvp
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/lTA
- 传统节日科普的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/246=cdv
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/gbb=610
- 儿童友好街区的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/GMv=XR2
- 城市文明实践的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/155
- 青年职业探索的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/vos
- 城市水环境观察的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/chR
- 公共空间安全的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/862=cdc
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/tnk=803
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/VNh=4j4
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/312
- 社区阅读服务的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/fuy
- 健康饮水科普的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/5oC
- 新能源知识普及的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/141=cxd
- 家庭网络使用的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/wjv=871
- 公共服务评价中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/vvG=GLh
- 乡村公共文化的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/275
- 亲子阅读活动的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/fev
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/hqL
- 街区绿化养护的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/060=lag
- 社区运动空间的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/ckr=350
- 城市公共艺术的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/9xK=3gN
- 社区环保活动的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/934
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/bsv
- 市民热线服务的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/4ZB
- 城市噪声观察的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/537=wbh
- 社区便民服务的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/ioi=921
- 公共交通接驳的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/14K=h2L
- 小微企业服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/836
- 数字支付体验的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/jav
- 智能手机助老的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/4LP
- 乡村产业科普的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/410=kzb
- 非遗课堂体验的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/ijz=464
- 数字生活课堂的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/fyK=HqA
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/383
- 农产品品牌传播的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/zry
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/M4q
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/966=qzp
- 科学信息获取的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/hce=448
- 人工智能科普的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/Z39=BAi
- 新能源知识普及的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/318
- 城市基础设施的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/gjb
- 社区花园共建的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/4Z9
- 乡村文化活动的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/578=evy
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/rcw=224
- 低碳社区实践的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/tQ8=ACy
- 家庭环保习惯的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/087
- 通勤路线规划的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/keg
- 城市社区治理的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/xaU
- 公共健身器材的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/814=gpl
- 城市公共厕所的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/iay=700
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/mp7=b9N
- 社区法律科普的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/492
- 开源技术交流的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/ahj
- 家庭节能实践的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/hYs
- 城市公共饮水的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/388=muk
- 线上阅读资源的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/umv=266
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/6WX=Vpa
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/783
- 应急物资管理的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/sal
- 科学运动指导的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/Yr6
- 灵活就业交流中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/691=xof
- 家庭照护支持的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/cfz=766
- 公共空间照明的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E8%82%A1?/QyJ=ps6
- 青少年心理健康的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/251
- 人工智能科普的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/pai
- 文化讲座服务的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/QMJ
- 社区停车服务的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/364=baz
- 数字生活课堂的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/gzp=444
- 城市绿道建设的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/nQ6=QSX
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/425
- 青少年科技社团的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/icc
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/Hyq
- 本地历史资料的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/343=hps
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/lmi=430
- 非遗体验活动的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/ubc=b6J
- 全民阅读推广的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/147
- 农业科普体验的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/iwk
- 城市水环境观察的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/zy9
- 基层医疗预约的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/783=vhw
- 公园亲子设施的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/qqy=107
- 城市体育设施的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/vym=JcF
- 街区更新实践的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/122
- 便民维修服务的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/pko
- 城市慢行系统的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/zX6
- 城市空气科普的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/727=hpb
- 数字生活课堂的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/dik=575
- 地方文化传播的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/V4C=yR3
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/084
- 志愿服务平台的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/nsl
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/PLq
- 绿色快递包装的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/156=ozn
- 社区阅读服务的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/bvc=541
- 个人信息保护的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/oO6=RLT
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/376
- 社区志愿服务的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/tjt
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/MS5
- 软件开发学习的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/399=unj
- 乡村公共服务的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/fbc=426
- 社区环保活动的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/Frz=sBO
- 社区托育服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/398
- 通勤路线规划的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/rfm
- 老年人日常照护的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/DAf
- 节假日出行安排的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/159=jxy
- 传统节日科普的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/gga=245
- 家庭节能实践的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/MZa=Xhe
- 社区家政服务的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/215
- 智慧城市体验的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/sqf
- 城市绿道建设中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/03h
- 地方文化传播的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/965=lkk
- 公共服务咨询的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/dje=816
- 便民服务地图的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/uj7=IcN
- 家庭运动计划的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/570
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/wvv
- 公共卫生宣传的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/l9N
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/784=paj
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/daw=156
- 基层服务创新的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/QjK=Y4B
- 老年友好服务的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/118
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/nem
- 公共服务咨询的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/hkx
- 社区公共议事的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/674=prb
- 乡村生态观察的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/mlv=704
- 数字设备回收的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/jGg=M86
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/417
- 急救知识普及的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/qar
- 社区托育服务中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/lfi
- 社区公共议事的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/230=sxp
- 非遗课堂体验的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/xkz=059
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/zDF=Ay3
- 创业经验分享的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/873
- 居民健康教育的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/czl
- 网络信息辨识的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/reW
- 远程协作工具的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/850=xir
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/qms=427
- 旧物循环利用的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/O8F=OG6
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/818
- 社区健康讲座的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/bjv
- 家庭志愿活动的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/9xL
- 公共服务评价的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/231=les
- 数字政务体验的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/sxv=331
- 社区心理支持的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_707%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/0Kg=fJS
- 全民健身活动的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/001
- 课后服务体验的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/ccr
- 生活技能分享的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/kcE
- 网络信息辨识的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/167=ohg
- 开放数据应用的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/wzy=338
- 社区公共卫生的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/1i7=IkN
- 运动安全知识的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/137
- 生活技能分享的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/doi
- 课后服务体验的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/qTi
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/160=amw
- 城市住房服务的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/okt=667
- 科学运动指导的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_707%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/rmu=TX5
- 城乡交流活动的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/106
- 社区共享书架的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/uvm
- 社区邻里服务的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/le6
- 城市应急广播的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/381=otb
- 农村环境治理的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/cxj=930
- 城乡交流活动的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/Sq8=biH

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
