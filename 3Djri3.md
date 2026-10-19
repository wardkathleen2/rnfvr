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

- 校园节能行动的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/Pcq
- 城市公共饮水的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/826=ljz
- 本地旅行体验的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/qqp=321
- 运动安全知识中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/Z7z=M5B
- 远程协作工具的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/375
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/vel
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/PLU
- 安全出行教育中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/719=ypu
- 城市人文观察的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/hxu=680
- 气象科普传播的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4?/X5w=9xd
- 数字档案服务的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/986
- 城市公共空间的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/pel
- 开放数据应用的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/vPl
- 校园安全教育的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/835=fhx
- 社区绿色空间的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/scd=826
- 乡村生活观察的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/QkG=0y0
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/088
- 科学信息获取的服务质量观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/ahc
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/MDD
- 社区读书角建设的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/877=ipc
- 乡村公共服务的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/ymn=469
- 城市噪声观察的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/Z52=WFw
- 市民热线服务的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/268
- 科学观察活动的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/bjg
- 乡村公共阅读的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/uco
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/462=htj
- 光伏知识科普的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/gfb=285
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/hj8=GoP
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/745
- 新能源出行从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/uhp
- 乡村产业科普的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/rK2
- 节气饮食文化的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/116=see
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/lar=204
- 乡村文化活动的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/pmY=Brv
- 城市生活服务的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/505
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/rtk
- 邻里互助活动的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/PmC
- 城市雨天出行的行动步骤参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/068=fzc
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/oci=449
- 公共交通接驳的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/1Pk=Wan
- 农村环境治理的日常使用指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/338
- 家庭收纳实践的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/azc
- 学校体育活动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/Wfb
- 城市步行友好的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/778=ohw
- 数据分析入门的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/igt=053
- 社区协商议事中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/rL5=MBZ
- 个人时间管理的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/574
- 户外活动组织的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/yin
- 家庭饮食安排的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/lut
- 城市步行环境的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/621=jvz
- 开放式学习空间的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/mho=955
- 社区体育组织的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/7BP=EQ2
- 数字支付体验的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/331
- 基层服务创新的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/djk
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/WTf
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/803=dqc
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/vre=415
- 城乡交通衔接的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/Zgy=93n
- 环境教育课程的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/716
- 公共空间安全的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/ape
- 绿色出行服务的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/H9F
- 社区法律科普的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/718=jht
- 乡村产业科普的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/emv=636
- 社区学习活动的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/89h=kB2
- 城市步行环境的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/079
- 数字课堂应用的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/dms
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/ngC
- 社区快递服务的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/326=ege
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/pxx=066
- 通勤路线规划的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/q5y=MJq
- 社区故事采集的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/879
- 青年就业服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/kpl
- 数字学习资源的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/qXR
- 口袋公园建设的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/923=yma
- 老年人出行服务的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/vsf=621
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/IMt=NWr
- 青少年户外教育的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/584
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/xoq
- 社区邻里服务的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/4G4
- 城市展览体验的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/316=qvz
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/zhc=247
- 社区科普课堂中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/oYz=w5a
- 亲子科普活动的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/761
- 基层服务创新的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/qcb
- 本地消费场景的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/7Wa
- 城市游园体验的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/120=ytk
- 城市博物馆服务的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/tqk=500
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/jDG=WOe
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/210
- 青少年心理健康的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/xte
- 科学信息获取的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/ZZG
- 社区活动策划的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/648=cwy
- 健康饮水科普的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/bdr=455
- 公共服务咨询的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/nwq=ZKb
- 青少年心理健康的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/477
- 社区教育资源的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/msq
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/xIA
- 网络安全教育的绿色实践方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/778=hsr
- 社区学习活动的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/wpp=962
- 社区环保活动的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/A3G=2fs
- 儿童友好空间的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/651
- 社区便民服务的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/xsz
- 社区修缮行动的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/clp
- 乡村公共服务的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/621=evu
- 社区读书角建设的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/zza=896
- 社区手工活动的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/C6F=JbZ
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/528
- 科学健身方法的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/bog
- 社区安全巡查的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/O0M
- 在线学习体验的设施维护观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/245=sos
- 便民服务地图的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/gtx=380
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/r5M=Yd4
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/466
- 公园亲子设施的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/mpp
- 智慧停车服务的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/S1I
- 环境教育课程的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/421=usg
- 社区文化节活动的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/rov=205
- 社区协商议事的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/8Ds=HZv
- 科学健身方法的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/135
- 城市噪声观察的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/xni
- 安全出行教育的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/m7z
- 儿童安全出行的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/549=crg
- 公共空间休憩的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/hbj=051
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/bUi=u0Y
- 城市住房服务的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/395
- 城市公共厕所的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/rdv
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/l7w
- 家庭消费规划的协商参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/139=sfv
- 城市生活记录的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/iii=022
- 绿色校园实践的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/o9t=FLb
- 社会体育指导的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/039
- 垃圾分类指导的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/fiw
- 公共服务数字化的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/ahN
- 市民热线服务的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/849=ahg
- 数字学习资源的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/xug=286
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/qP3=q5Z
- 基层服务创新的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/372
- 智能手机助老的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/wpm
- 新能源出行的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/V91
- 网络信息辨识的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/289=sjf
- 职业技能学习的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/hkx=774
- 社区手工活动的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/15O=BTn
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/201
- 社区学习活动的适老服务细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/vte
- 社区快递服务的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/doU
- 小区电梯维护的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/704=dta
- 健康信息获取的流程优化思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/fcd=681
- 社区知识分享的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/VKN=nKD
- 生活垃圾回收的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/476
- 周末休闲规划的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/jra
- 开源技术交流的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/Pzm
- 城市住房服务的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/143=rhg
- 家庭急救准备的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/smk=636
- 公共服务评价的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/nB0=fCs
- 地方美食文化的空间设计要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/252
- 城市慢跑路线的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/umh
- 老年人日常照护的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/PlR
- 城市公共艺术的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/250=kup
- 社区家政服务的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/aas=142
- 生活技能分享的服务细节记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/kzG=9XV
- 图书借阅体验中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/757
- 农业科普体验的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/wxh
- 社区公共卫生的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/uva
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/378=owl
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/tia=863
- 地方文化传播的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/Pg8=KY0
- 老年智能设备的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/305
- 应急物资管理的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/txf
- 居民健康教育中的沟通与协作 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/PAe
- 电子商务服务的参与方式与路径 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/023=awb
- 城市绿色交通的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/xhp=123
- 乡村产业科普的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/96A=MJI
- 儿童运动体验的活动体验回顾 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/586
- 公交站点体验的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/ohd
- 老年人日常照护的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/fso
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/300=ekn
- 城乡交流活动的基础设施观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/nhj=119
- 公共服务预约的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%88%9B%E6%8A%95?/FUC=upc
- 图书馆数字服务的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/751
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/dfw
- 数字学习资源的家庭参与方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/oDC
- 社区体育组织的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/663=kpw
- 数字支付体验的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/eun=917
- 老年友好服务的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/OOY=gPL
- 新能源知识普及的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/975
- 公共文化活动的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/swq
- 便民信息查询的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/3a6
- 城市夜间生活的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/703=vwi
- 社区宠物管理的线下体验记录 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/kqu=405
- 社区修缮行动的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/y5u=CSk
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/492
- 社区绿色空间的日常记录与分享 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/uzq
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/MEq
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/665=onv
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/suh=353
- 社区便民集市的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/BlW=1sK
- 社区信息发布的公共参与指南 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/851
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/una
- 公共服务数字化的数字化应用观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/wFU
- 家庭健康科普的组织方法与经验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/619=uol
- 公园亲子设施的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/rxn=501
- 智能手机助老的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/O2F=Z8T
- 公共空间安全的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/294
- 城市雨天出行的活动策划思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ftz
- 地方民俗记录的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/bmz
- 社区安全巡查的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/555=kry
- 城市绿色交通的实用信息清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ggs=078
- 公共文化活动的学习资源整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/H3V=G2i
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/780
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/qxr
- 公共空间休憩的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/dv3
- 小区公共照明的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/888=sxb
- 城市共享单车的便捷程度观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/ray=227
- 绿色办公实践的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/C4M=JHD
- 科学运动指导的便利性观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/170
- 数字学习资源的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/ynv
- 网络信息辨识的便民做法梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/lEA
- 校园安全教育的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/521=isf
- 社区养老服务的居民参与机会 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/uuj=894
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/5CE=7ls
- 城市树木认养的社区行动案例 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/205
- 乡村生态旅游的入门知识整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/rjb
- 社区阅读服务的服务体验观察 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/zyc
- 创业经验分享的资源利用方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/555=rjp
- 数字公共文化的服务范围梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/vfu=778
- 智慧城市体验的日常实践笔记 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/a9t=IGs
- 开放数据应用的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/561
- 数字艺术创作的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/zmp
- 城市噪声观察的日常管理方法 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/Sig
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/140=shx
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/vhe=279
- 无障碍信息设计的持续改进方向 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/CzP=9aQ
- 社区科普课堂的家庭实践清单 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/595
- 家庭饮食安排的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/uwz
- 市民热线服务的实际需求与回应 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/Moc
- 乡村生活观察的资源整合思路 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/190=cdm
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/ynp=231
- 节约用水实践的长期维护要点 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/D6E=5rB
- 城乡交流活动的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/160
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/ciy
- 青少年户外教育的基础知识问答 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/cqD
- 数字便民地图中的几个关键细节 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/465=syy
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/yqt=359
- 社区知识分享的服务反馈渠道 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1?/HjJ=LIa
- 社区家校合作的执行流程参考 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/295
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/lou
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/70S
- 健康饮水科普的空间使用体验 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/200=bmy
- 乡村生态旅游的服务信息整理 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/slz=892
- 运动安全知识的安全使用提示 |来源：https://github.com/hooperbenjamin7833/earg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/Meg=Cpg

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
