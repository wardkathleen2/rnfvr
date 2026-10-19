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

- 学校食育活动的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/673
- 家庭教育交流的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/hyk
- 公共空间休憩的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/Kcr
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/952=tpw
- 生活服务数字化的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/bge=332
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/Gi2=ah3
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/666
- 公共服务咨询的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/imz
- 老旧小区改造的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/fP5
- 生活技能分享的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/919=vlr
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/ulj=781
- 邻里互助活动的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/ZuC=Gbe
- 公共服务评价的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/049
- 家庭网络使用的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/ygb
- 科普展览体验的数字工具使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/bLj
- 社区便民集市的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/486=lzv
- 城市建设科普的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/pie=187
- 家庭食品保存的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%90%88%E7%90%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/2Ec=SuL
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/843
- 城市人文观察的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/opc
- 城市应急广播中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/1ip
- 校园节能行动的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/039=mtf
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/xoe=735
- 社区公共餐饮的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/YLX=SAU
- 公共服务沟通的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/818
- 城市文化路线的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/kix
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/MfV
- 家庭网络使用的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/878=irg
- 劳动教育实践的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/qrn=155
- 社区读书角建设的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/L0y=sfm
- 科技馆参观体验的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/459
- 数字阅读服务的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/ipb
- 社区设施共享的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/4iz
- 网络信息辨识的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/807=itx
- 网络安全教育的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/ljv=701
- 城乡公共服务的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/c5X=n51
- 全民阅读推广的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/711
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/iva
- 开放数据应用的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/uER
- 网络安全教育的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/530=zuq
- 节能生活方式的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/bym=192
- 乡村生活观察的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/wNf=sKH
- 社区垃圾回收的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/523
- 城乡公共服务的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/nzo
- 城市微更新实践的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/gGr
- 数字资源检索的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/796=dts
- 乡村生态观察中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/yoi=819
- 终身学习资源的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/rpl=5qD
- 公共卫生设施的便民做法梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/653
- 绿色消费选择的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/zij
- 数字政务体验的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/f0U
- 校园阅读活动的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/927=rci
- 环境教育课程的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/ncz=569
- 城市水环境观察的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/Pt2=2wp
- 社区商业活力的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/356
- 劳动教育实践的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/sxd
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/NEi
- 小区公共照明的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/185=hcm
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/fpz=234
- 线上阅读资源的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E4%BB%80%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/Pjn=NVG
- 社区公共卫生中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/557
- 本地消费场景中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/kuf
- 社区快递服务的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/MAh
- 家庭安全提示的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/435=nes
- 街区更新实践的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/xiv=484
- 公共服务预约的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%89%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/3tP=mSC
- 志愿者培训交流的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/445
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/zod
- 城市建设科普的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/Ps1
- 绿色办公实践的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/783=cpd
- 青少年科技社团的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/thg=667
- 就业技能培训的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88Q_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/z2C=ipD
- 生活服务数字化的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/289
- 社区学习活动的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/rbh
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/j1i
- 家庭安全提示的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/246=rmj
- 城市生活服务的服务体验观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/hxi=581
- 创业经验分享的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/xli=3QO
- 无障碍出行的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/273
- 数据分析入门的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/doe
- 社区科普课堂的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/4oF
- 绿色出行服务的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/302=yxl
- 老年友好服务的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/oax=220
- 青少年科普实践的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%88%86%E4%BC%97%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/uJi=Yg4
- 非遗体验活动的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/509
- 社区体育组织的服务质量观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/cmg
- 城市步行友好中的几个关键细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/6Wa
- 社会体育指导的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/898=jpp
- 创业经验分享的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/nem=820
- 健康饮水科普的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/nMs=09K
- 健康饮食教育的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/177
- 食品配送体验的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/tht
- 社区交通安全的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/FhE
- 新能源知识普及的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/765=dke
- 公共设施使用的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/jdc=582
- 家庭养老规划的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/0ho=Non
- 医院导诊服务的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/822
- 生活技能分享的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/tik
- 社区互助网络的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/ogb
- 儿童安全出行的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/086=aad
- 农产品消费体验的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/mhr=834
- 课后服务体验的参与方式与路径 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/Uuy=11K
- 亲子科普活动的常见问题梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/718
- 城市文化路线的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/eqz
- 本地旅行体验的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/sjg
- 租房信息服务的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/686=klk
- 社区设施共享的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/wsr=431
- 家庭阅读计划的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/Xs1=FGf
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/807
- 街区道路维护的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/ctk
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/hXA
- 低碳社区实践的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/201=vdc
- 环境教育课程的服务细节记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/ysr=253
- 城乡公共服务的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Ma3=2fM
- 城市水环境观察的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/964
- 数字生活课堂的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/cfb
- 城市体育设施的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/Gfr
- 城市骑行环境的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/438=bxn
- 社区商业活力的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/mxl=635
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/FdQ=HYl
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/789
- 儿童户外活动的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/tqy
- 街区道路维护的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/IKC
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/387=fsj
- 在线教育体验的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/ebp=327
- 城市地名文化的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/mY0=5W1
- 儿童友好空间的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/532
- 环境监测科普的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/xuz
- 小区公共照明的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/oUL
- 全民阅读推广的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/699=rdu
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/gvn=226
- 数字支付体验的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/fru=ZnP
- 社区活动空间的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/348
- 地方民俗记录的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/edc
- 城市适老服务的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/aI3
- 数字素养提升的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/788=tql
- 社区艺术活动的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/eai=689
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/GVx=oXu
- 物业服务沟通的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/905
- 城市微更新实践的儿童友好细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/cfq
- 公共交通信息服务的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/R39
- 居家适老化改造的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/807=yic
- 社区绿色空间的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/kln=482
- 智能家居应用中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/K9c=kkB
- 亲子阅读活动的社区参与观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/507
- 本地消费场景的协商参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/jle
- 生成式工具使用的常见误区提醒 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/vnk
- 社区共享书架的实际需求与回应 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/538=eny
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/ohl=127
- 安全出行教育的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80%E4%B8%80%E8%88%AC%E5%A4%9A%E4%B9%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/Qxv=ik5
- 节假日出行安排的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/556
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/ucv
- 城市微更新实践的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/5wN
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/247=stn
- 公共健身器材的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/jqh=822
- 乡村生态旅游的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/1C9=6Tu
- 公园休闲体验的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/704
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/xtx
- 社区公共议事的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/Srz
- 便民维修服务的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/141=uaz
- 城市游园体验的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/lxz=446
- 课后服务体验的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1qq_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/pRN=tjN
- 健康饮食教育的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/219
- 开放数据应用的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/jac
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/KZu
- 乡村公共阅读的居民参与机会 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/551=roo
- 科学信息获取的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/jmm=196
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/j2Z=Zkq
- 城市博物馆服务的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/462
- 邻里互助活动的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/vir
- 社区活动策划的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/gNi
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/061=rco
- 社区知识分享的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/azi=164
- 本地消费场景的学习资源整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/83G=ZsR
- 数字创意课程的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/695
- 公共健身器材的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/yap
- 数字地图应用的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/TTI
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/076=ckf
- 青少年科普实践的日常实践笔记 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/fxd=580
- 校园阅读活动的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/5ay=ykY
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/587
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/kua
- 老年运动活动的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/zPG
- 节假日出行安排的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/991=fby
- 老年智能设备的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/avc=729
- 青少年户外教育的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92QQ%E7%BE%A4_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/M5y=ypt
- 家庭消费规划的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/620
- 家庭教育交流的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/glt
- 社区环保活动的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/w6q
- 社区托育服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/577=abr
- 城市公共饮水的活动组织技巧 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/zzw=279
- 家庭科学教育的服务信息整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%BD%AF%E4%BB%B6%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/APg=db5
- 线上办事服务的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/835
- 非遗体验活动的行动步骤参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/trd
- 城市应急科普的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/M4V
- 城乡交流活动的空间设计要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/321=pxy
- 社区防暑服务的入门知识整理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/azz=732
- 社区停车服务的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/UBc=eVH
- 应急物资管理的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/903
- 旧物循环利用的活动策划思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/rus
- 城市文明出行的空间使用体验 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/Mxd
- 骑行路线规划的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/591=bxc
- 城市公共标识的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/iii=716
- 电动汽车充电的流程优化思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/Pm4=n5C
- 居民健康教育的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/301
- 节能生活方式的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/wte
- 街头绿植养护的便利性观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/f6K
- 家庭志愿活动的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/774=vcz
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/kfg=359
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/eSr=Cq7
- 城市建设科普的实用信息清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/712
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/ooy
- 租房信息服务的基础知识问答 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/T7k
- 社区宠物管理的公共参与指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/511=wur
- 老年运动活动的资源利用方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/qkb=675
- 绿色出行服务的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AA%97%E5%B1%80_360%E7%9B%B4%E6%92%AD?/c04=MaV
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/060
- 绿色出行服务的协作机制梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/olz
- 无障碍信息设计的设施维护观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/a2q
- 社区学习活动的家庭参与方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/047=rhe
- 社区快递服务的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/sxb=067
- 文明养宠科普的日常记录与分享 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/8EG=WaI
- 公共交通接驳的长期维护要点 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/598
- 传统节日科普的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/jon
- 本地消费场景的服务范围梳理 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/8iO
- 城市基础设施的便捷程度观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/463=ygj
- 数字政务体验的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/sul=310
- 社区协商议事的活动体验回顾 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/Vmy=wqm
- 绿色校园实践的资源整合思路 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/407
- 街区更新实践中的沟通与协作 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/rcw
- 公共服务数字化的家庭实践清单 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/I0U
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/658=ywl
- 社区公共议事的社区行动案例 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/kfk=414
- 城市水环境观察的持续改进方向 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/5bz=DAA
- 乡村阅读活动的执行流程参考 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/543
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/jdn
- 绿色建筑理念的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/ekk
- 开放式学习空间的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/989=bov
- 社区志愿服务的数字化应用观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/yjc=402
- 文明养宠科普的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/De4=vSU
- 农贸市场环境的日常使用指南 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/311
- 读书会组织从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/cqn
- 个人数据管理的基础设施观察 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/v7l
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/012=dhi
- 老旧小区改造的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/vds=313
- 基层服务创新的日常管理方法 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/zrR=dDK
- 数字艺术创作的安全使用提示 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/573
- 数字阅读服务的适老服务细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/vwr
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/s37
- 健康饮水科普的线下体验记录 |来源：https://github.com/wilsonrebecca374/zoid/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/699=jzy

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
