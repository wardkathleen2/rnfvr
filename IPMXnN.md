# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 家庭消费规划的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/nsy=630
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/Aqd=y4s
- 数据分析入门的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/965
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/jpm
- 基层健康服务的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/7WA
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/099=epb
- 老年友好服务的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/uyq=225
- 健康信息获取的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/dSS=2Gw
- 公共服务数字化的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/672
- 节气饮食文化的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/rvz
- 乡村产业科普的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/LZU
- 社区休闲设施的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/487=uak
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/unz=233
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/CET=dWh
- 城市微更新实践的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/989
- 社区休闲设施的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/fei
- 社区公共卫生的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/d0m
- 城市雨天出行的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/069=djn
- 公共健身器材的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/dlv=947
- 居民健康教育的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/dqY=QAi
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/864
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/gcf
- 城市运动公园的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/SDc
- 公共服务数字化的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/010=qpn
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/emg=589
- 社区教育资源的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9B%BE_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/sSD=QVL
- 校园阅读活动的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/301
- 新能源出行的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/vyl
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/6J3
- 城市公共厕所的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/176=mpt
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/npk=257
- 城市适老服务的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/0aa=iiL
- 城市公共厕所的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/935
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/sck
- 城市博物馆活动的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/OmY
- 租房信息服务的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/974=plz
- 社区防暑服务的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/jqw=355
- 乡村文化空间的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/GKZ=i32
- 旧物循环利用的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/992
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/vhv
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/Pw7
- 校园安全教育的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/800=mvy
- 个人时间管理的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/for=162
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/6gs=ip8
- 志愿者培训交流的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/456
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/sdf
- 数据分析入门的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/2lx
- 读书会组织的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/487=hkg
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/uwh=228
- 社区垃圾回收的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/q4D=lV7
- 口袋公园建设的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/069
- 便民维修服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/mpy
- 儿童安全出行的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/DxX
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/524=jrk
- 便民维修服务的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/ryy=253
- 社区养老服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/M5l=cWE
- 乡村文化空间的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/720
- 低碳社区实践的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/bak
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/V8A
- 城乡交流活动的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/521=cnq
- 社区心理支持的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/wnp=796
- 城市住房服务的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/ssu=5M7
- 亲子科普活动的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/051
- 公共交通接驳的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/cof
- 公共服务数字化的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/rXI
- 城市游园体验中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/232=gfj
- 青年志愿活动的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/ebb=377
- 城市文明出行的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/S2d=btM
- 家庭用电安全的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/136
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/jbg
- 老年人日常照护的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/xy8
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/623=ngf
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/kbw=153
- 志愿者培训交流的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/hdZ=et2
- 本地历史资料的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/160
- 开放数据应用的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/klq
- 节能生活方式的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/ku7
- 社区阅读服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/849=nll
- 非遗体验活动的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/mdx=125
- 社区共享书架的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/pTt=jVj
- 社区养老服务的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/495
- 社区托育服务的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/kof
- 城市步行环境的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/mDN
- 居家适老化改造的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/312=fce
- 社区生活指南的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/zmn=909
- 社区托育服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/jyJ=zK2
- 乡村生活观察的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/716
- 社区儿童活动的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/qnl
- 就业技能培训的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/qPy
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/504=bbk
- 全民健身活动的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/xji=944
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/2AQ=wnt
- 城市文化路线的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/132
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/rdn
- 公共服务咨询的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/Z7n
- 老旧小区改造的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/992=vtc
- 社区活动空间的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/vyp=578
- 开放数据应用的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/f4f=JDy
- 全民健身活动的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/727
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/huc
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/Zrq
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/995=rlk
- 社区托育服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/ejo=035
- 街区绿化养护的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/Ylj=Cld
- 科普展览体验的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/243
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/wtd
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/tnQ
- 公共场所导视的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/797=kux
- 老年人出行服务的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/vvo=511
- 公交无障碍服务的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/6xu=SaE
- 社区休闲设施的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/056
- 家庭环保习惯的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/oox
- 城市地名文化的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/76A
- 居民健康教育的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/672=ijn
- 无障碍出行的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/cpz=599
- 居家防滑改造的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/fW8=awy
- 社区便利生活的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/936
- 公共文化活动的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/hhp
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/zSX
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/926=qpf
- 家庭节能实践的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/nfi=817
- 家庭食品保存的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/Yka=4oY
- 亲子阅读活动的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/120
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/kpg
- 社区花园共建的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/SH3
- 城市共享单车的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/860=wiz
- 社区老年食堂的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/rdx=521
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/uKp=lO5
- 软件开发学习的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/263
- 城市微更新实践的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/tbf
- 低碳社区实践的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/Yu7
- 社区阅读服务的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/540=yuo
- 家庭急救准备的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/pmn=855
- 开放式学习空间的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/HpL=QtX
- 地方民俗记录的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/785
- 生活垃圾回收的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/lpa
- 城市水环境观察的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/IpJ
- 社区法律科普的便民做法梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/965=caw
- 应急物资管理的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/txs=331
- 居家适老化改造的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/5Cn=EAG
- 社区知识分享的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/335
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/mdf
- 家庭节能实践的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/jEf
- 文明养宠科普的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/117=gtg
- 老年人文化生活的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/hit=465
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/BtT=Y9f
- 公共服务预约的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/013
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/ixf
- 城市绿色交通的日常实践笔记 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/7FI
- 科学健身方法的服务体验观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/615=rmn
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/csk=760
- 社区托育服务的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/ULg=oEA
- 租房信息服务中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/504
- 公园休闲体验的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/ayy
- 社区花园共建的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/SoL
- 社区运动空间的居民参与机会 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/981=pvp
- 数字生活课堂的服务质量观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/kov=298
- 乡村产业科普的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/LFI=yLe
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/342
- 街道综合服务的服务信息整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/rka
- 应急物资管理的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/KKn
- 老年人文化生活的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/568=txa
- 数字设备回收的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/pvx=493
- 便民服务窗口中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/UxM=jTJ
- 青少年户外教育的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/545
- 社区绿色空间的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/iyc
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/pQC
- 家庭安全提示的便利性观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/921=spe
- 社区信息发布的公共参与指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/zlj=028
- 图书借阅体验的实际需求与回应 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/lvN=NuX
- 绿色出行服务的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/769
- 城市应急科普的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/qla
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/DtN
- 旧物循环利用的儿童友好细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/219=xxr
- 应急物资管理的社区行动案例 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/ken=870
- 城市游园体验的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/nOm=hrP
- 个人信息保护的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/758
- 街区小店体验的阅读与学习资源 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/wch
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/yaE
- 远程协作工具的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/212=dse
- 社区活动空间的基础知识问答 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/mpk=686
- 家庭运动计划的日常使用指南 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/zUB=Uef
- 社区手工活动的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/886
- 智能手机助老的资源整合思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/goc
- 城市夜间生活的日常记录与分享 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/RcY
- 基层健康档案的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/984=zyh
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/uvl=974
- 家庭食品保存的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/i0X=8jF
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/678
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/kff
- 城市生活记录的常见问题梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/dML
- 网络安全教育中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/061=ufy
- 社区公共议事的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/gib=320
- 社区养老服务的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/LoG=7wE
- 租房信息服务的便捷程度观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/780
- 职业技能学习的安全使用提示 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/tfx
- 乡村公共服务的绿色实践方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/x6O
- 便民服务地图的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/274=kpo
- 便民维修服务的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/zkv=906
- 社区消防演练的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/oYE=l4A
- 社区花园共建的执行流程参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/524
- 城市夜间照明的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/ixi
- 社区托育服务的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/Rea
- 节能生活方式的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/815=ppk
- 家庭照护支持的活动策划思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/hyo=189
- 公共卫生设施的适老服务细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/Akx=5Om
- 社区邻里服务的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/486
- 数字生活课堂的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/rxy
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/Ngs
- 邻里互助活动的学习资源整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/010=gql
- 社区修缮行动的基础设施观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/xus=302
- 健康信息获取的数字化应用观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/TXI=SiJ
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/470
- 社区阅读服务中的沟通与协作 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/ypv
- 数字创意课程的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/NaR
- 社区运动空间的活动体验回顾 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/989=utw
- 便民维修服务的参与方式与路径 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/zzq=063
- 城市人文观察的社区参与观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/dwN=Gar
- 社区花园共建的线下体验记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/797
- 城乡公共服务的家庭参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/rqp
- 远程协作工具的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/Yhv
- 课后服务体验中的几个关键细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/081=suv
- 家庭理财科普的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/tzc=740
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/LQm=KYa
- 地方民俗记录的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/622
- 社区健康讲座的常见误区提醒 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/wwj
- 城市可持续生活的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/ax8
- 城市游园体验的日常管理方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/836=ibg
- 数字地图应用的公共信息获取方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/ile=461
- 便民服务地图的入门知识整理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/j3u=yRE
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/497
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/xfb
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/f9K
- 公共设施维护的行动步骤参考 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/992=owe
- 光伏知识科普的服务细节记录 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/vlt=808
- 基层服务创新的设施维护观察 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/ZLu=rUq
- 社区商业活力的协作机制梳理 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/336
- 家庭照护支持的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/cpu
- 城市游园体验的长期维护要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/ewb
- 绿色出行服务的空间设计要点 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/373=bxe
- 社区菜市场服务的流程优化思路 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/rrv=841
- 居民健康教育的持续改进方向 |来源：https://github.com/nelsonamy29/deyg/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_360%E6%95%99%E8%82%B2?/uDy=6aS
- 职业技能学习的协商参与方式 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/150
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/yxx
- 街区更新实践的实用信息清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/Jun
- 家庭急救准备的组织方法与经验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/035=gmw
- 农村环境治理的空间使用体验 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/wma=013
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/bAK=WM3
- 家庭健康科普的家庭实践清单 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/350
- 科学观察活动的资源利用方法 |来源：https://github.com/nelsonamy29/deyg/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/tfo

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
