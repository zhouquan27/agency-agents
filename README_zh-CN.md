# 🎭 The Agency：随时待命的 AI 专家团队

> **触手可及的完整 AI 智能体团队** —— 从前端高手到 Reddit 社区忍者，从灵感注入者到现实核查员。每位智能体都是拥有鲜明个性、成熟工作流和可交付成果的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

[English](README.md) | 简体中文 | [贡献指南（中文）](CONTRIBUTING_zh-CN.md)

---

## 🚀 这是什么？

**The Agency** 起源于 Reddit 上的一个帖子，经过数月迭代打磨，现已发展为一套精心设计的 AI 智能体个性集合。每位智能体：

- **🎯 高度专业化**：深耕所在领域（而非泛泛的提示词模板）
- **🧠 个性鲜明**：独特的声音、沟通风格和解决方式
- **📋 交付导向**：真实代码、完整流程和可量化的结果
- **✅ 生产就绪**：经过实战检验的工作流和成功指标

**可以把它理解为**：组建你的梦之团队，只不过这些 AI 专家永不休眠、从不抱怨，而且随时交付。

---

## ⚡ 快速开始

### 方式一：与 Claude Code 配合使用（推荐）

```bash
# 将智能体文件复制到 Claude Code 目录
cp -r agency-agents/* ~/.claude/agents/

# 在 Claude Code 会话中激活任意智能体：
# "嘿 Claude，切换到前端开发者模式，帮我构建一个 React 组件"
```

### 方式二：作为参考资料

每个智能体文件包含：
- 身份与个性特征
- 核心使命与工作流
- 含代码示例的技术交付物
- 成功指标与沟通风格

浏览下方智能体列表，按需复制和调整即可！

### 方式三：与其他工具配合（Cursor、Aider、Windsurf、Gemini CLI、OpenCode、Kimi Code）

```bash
# 第一步 —— 为所有支持的工具生成集成文件
./scripts/convert.sh

# 第二步 —— 交互式安装（自动检测已安装工具）
./scripts/install.sh

# 或直接指定特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool kimi
```

---

## 🎨 智能体阵容

### 💻 工程部

构建未来，一次提交一步。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎨 [前端开发者](engineering/engineering-frontend-developer.md) | React/Vue/Angular、UI 实现、性能优化 | 现代 Web 应用、像素级 UI、Core Web Vitals 优化 |
| 🏗️ [后端架构师](engineering/engineering-backend-architect.md) | API 设计、数据库架构、可扩展性 | 服务端系统、微服务、云基础设施 |
| 📱 [移动应用构建者](engineering/engineering-mobile-app-builder.md) | iOS/Android、React Native、Flutter | 原生和跨平台移动应用 |
| 🤖 [AI 工程师](engineering/engineering-ai-engineer.md) | ML 模型、部署、AI 集成 | 机器学习功能、数据管道、AI 驱动应用 |
| 🚀 [DevOps 自动化专家](engineering/engineering-devops-automator.md) | CI/CD、基础设施自动化、云运维 | 流水线开发、部署自动化、监控 |
| ⚡ [快速原型工程师](engineering/engineering-rapid-prototyper.md) | 快速 POC 开发、MVP | 概念验证、黑客马拉松项目、快速迭代 |
| 💎 [高级开发者](engineering/engineering-senior-developer.md) | Laravel/Livewire、高级模式 | 复杂实现、架构决策 |
| 🔒 [安全工程师](engineering/engineering-security-engineer.md) | 威胁建模、安全代码审查、安全架构 | 应用安全、漏洞评估、安全 CI/CD |
| 🚨 [事故响应指挥官](engineering/engineering-incident-response-commander.md) | 事故管理、事后复盘、值班 | 管理生产事故，建立事故响应机制 |
| 📚 [技术文档撰写者](engineering/engineering-technical-writer.md) | 开发者文档、API 参考、教程 | 清晰准确的技术文档 |
| 💬 [微信小程序开发者](engineering/engineering-wechat-mini-program-developer.md) | 微信生态、小程序、支付集成 | 为微信生态系统构建高性能应用 |
| 👁️ [代码审查者](engineering/engineering-code-reviewer.md) | 建设性代码审查、安全、可维护性 | PR 审查、代码质量把关、代码辅导 |
| 🗄️ [数据库优化师](engineering/engineering-database-optimizer.md) | 模式设计、查询优化、索引策略 | PostgreSQL/MySQL 调优、慢查询调试、迁移规划 |
| 🏛️ [软件架构师](engineering/engineering-software-architect.md) | 系统设计、DDD、架构模式、权衡分析 | 架构决策、领域建模、系统演进策略 |
| 🛡️ [SRE](engineering/engineering-sre.md) | SLO、错误预算、可观测性、混沌工程 | 生产可靠性、减少重复劳动、容量规划 |
| 🔗 [飞书集成开发者](engineering/engineering-feishu-integration-developer.md) | 飞书/Lark 开放平台、机器人、工作流 | 为飞书生态系统构建集成 |
| 🧱 [CMS 开发者](engineering/engineering-cms-developer.md) | WordPress & Drupal 主题、插件/模块、内容架构 | 代码优先的 CMS 实现和定制 |

### 🎨 设计部

打造美观、易用、令人愉悦的体验。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎯 [UI 设计师](design/design-ui-designer.md) | 视觉设计、组件库、设计系统 | 界面创作、品牌一致性、组件设计 |
| 🔍 [UX 研究员](design/design-ux-researcher.md) | 用户测试、行为分析、研究 | 了解用户、可用性测试、设计洞察 |
| 🏛️ [UX 架构师](design/design-ux-architect.md) | 技术架构、CSS 系统、实现 | 开发者友好的基础、实现指导 |
| 🎭 [品牌守护者](design/design-brand-guardian.md) | 品牌标识、一致性、定位 | 品牌战略、标识开发、指导方针 |
| ✨ [奇思注入者](design/design-whimsy-injector.md) | 个性、愉悦感、趣味互动 | 添加乐趣、微互动、彩蛋、品牌个性 |
| 🌈 [包容视觉专家](design/design-inclusive-visuals-specialist.md) | 多样代表性、偏见消除、真实图像 | 生成文化准确的 AI 图像和视频 |

### 💰 付费媒体部

将广告预算转化为可量化的商业成果。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 💰 [PPC 活动策略师](paid-media/paid-media-ppc-strategist.md) | Google/Microsoft/Amazon Ads、账户架构、竞价 | 账户搭建、预算分配、规模增长、性能诊断 |
| 🔍 [搜索词分析师](paid-media/paid-media-search-query-analyst.md) | 搜索词分析、否定关键词、意图映射 | 词查审计、消除无效消耗、关键词发掘 |
| 📋 [付费媒体审计员](paid-media/paid-media-auditor.md) | 200+ 项账户审计、竞争对手分析 | 账户接管、季度审查、竞品提案 |
| ✍️ [广告创意策略师](paid-media/paid-media-creative-strategist.md) | RSA 文案、Meta 创意、PMax 素材 | 创意上线、测试项目、广告疲劳刷新 |
| 📱 [付费社交策略师](paid-media/paid-media-paid-social-strategist.md) | Meta、LinkedIn、TikTok、跨平台社交 | 社交广告项目、平台选择、受众策略 |

### 💼 销售部

通过专业能力（而非 CRM 杂务）将商机转化为营收。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎯 [外向销售策略师](sales/sales-outbound-strategist.md) | 信号驱动的潜客挖掘、多渠道序列、ICP 定向 | 通过研究驱动的外呼（而非海量轰炸）建立商机管道 |
| 🔍 [探索教练](sales/sales-discovery-coach.md) | SPIN、Gap Selling、Sandler 等问题设计与通话结构 | 准备探索性通话、筛选机会、辅导销售代表 |
| ♟️ [交易策略师](sales/sales-deal-strategist.md) | MEDDPICC 资格认定、竞争定位、赢单计划 | 评估交易、识别管道风险、制定赢单策略 |
| 📊 [管道分析师](sales/sales-pipeline-analyst.md) | 预测、管道健康度、交易速度、RevOps | 管道审查、预测精度、营收运营 |

### 📢 营销部

一次真诚互动，持续扩大受众规模。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🚀 [增长黑客](marketing/marketing-growth-hacker.md) | 快速用户获取、病毒循环、实验 | 爆发性增长、用户获取、转化率优化 |
| 📝 [内容创作者](marketing/marketing-content-creator.md) | 多平台内容、编辑日历 | 内容战略、文案写作、品牌叙事 |
| 🐦 [Twitter 互动专家](marketing/marketing-twitter-engager.md) | 实时互动、思想领导力 | Twitter 策略、LinkedIn 活动、专业社交 |
| 📱 [TikTok 策略师](marketing/marketing-tiktok-strategist.md) | 病毒内容、算法优化 | TikTok 增长、病毒内容、Z 世代/千禧一代受众 |
| 📸 [Instagram 策展人](marketing/marketing-instagram-curator.md) | 视觉叙事、社区建设 | Instagram 策略、美学发展、视觉内容 |
| 🤝 [Reddit 社区建设者](marketing/marketing-reddit-community-builder.md) | 真实互动、价值驱动内容 | Reddit 策略、社区信任、真实营销 |
| 📕 [小红书专家](marketing/marketing-xiaohongshu-specialist.md) | 生活方式内容、趋势驱动策略 | 小红书增长、美学叙事、Z 世代受众 |
| 💬 [微信公众号运营](marketing/marketing-wechat-official-account.md) | 粉丝互动、内容营销 | 公众号策略、社区建设、转化优化 |
| 🧠 [知乎策略师](marketing/marketing-zhihu-strategist.md) | 思想领导力、知识驱动互动 | 知乎权威建设、问答策略、线索生成 |
| 🇨🇳 [百度 SEO 专家](marketing/marketing-baidu-seo-specialist.md) | 百度优化、中国 SEO、ICP 合规 | 百度排名优化，触达中国搜索市场 |
| 🎬 [哔哩哔哩内容策略师](marketing/marketing-bilibili-content-strategist.md) | B 站算法、弹幕文化、UP 主增长 | 以社区优先的内容在 B 站建立受众 |
| 🛒 [中国电商运营](marketing/marketing-china-ecommerce-operator.md) | 淘宝、天猫、拼多多、直播电商 | 多平台中国电商运营 |
| 🎥 [快手策略师](marketing/marketing-kuaishou-strategist.md) | 快手、老铁社区、草根增长 | 在下沉市场建立真实受众 |
| 🔍 [SEO 专家](marketing/marketing-seo-specialist.md) | 技术 SEO、内容策略、链接建设 | 推动可持续的自然搜索增长 |
| 🎵 [抖音策略师](marketing/marketing-douyin-strategist.md) | 抖音平台、短视频营销、算法 | 在中国领先短视频平台上增长受众 |
| 🎙️ [直播电商教练](marketing/marketing-livestream-commerce-coach.md) | 主播培训、直播间优化、转化 | 构建高绩效直播电商运营 |
| 🔒 [私域运营师](marketing/marketing-private-domain-operator.md) | 企业微信、私域流量、社群运营 | 构建企业微信私域生态系统 |
| 🔥 [微博策略师](marketing/marketing-weibo-strategist.md) | 新浪微博、热搜话题、粉丝互动 | 全方位微博运营与增长 |
| 🇨🇳 [中国市场本地化策略师](marketing/marketing-china-market-localization-strategist.md) | 全栈中国市场本地化、抖音/小红书/微信 GTM | 将趋势信号转化为可执行的中国进入市场策略 |
| 🎬 [视频优化专家](marketing/marketing-video-optimization-specialist.md) | YouTube 算法策略、章节设计、缩略图 | YouTube 频道增长、视频 SEO、受众留存优化 |

### 📊 产品部

在正确的时间构建正确的东西。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎯 [冲刺优先级排定师](product/product-sprint-prioritizer.md) | 敏捷规划、功能优先级 | 冲刺规划、资源分配、待办事项管理 |
| 🔍 [趋势研究员](product/product-trend-researcher.md) | 市场情报、竞争分析 | 市场调研、机会评估、趋势识别 |
| 💬 [反馈综合器](product/product-feedback-synthesizer.md) | 用户反馈分析、洞察提炼 | 反馈分析、用户洞察、产品优先级 |
| 🧭 [产品经理](product/product-manager.md) | 全生命周期产品所有权 | 探索、PRD、路线图规划、GTM、结果衡量 |

### 🎬 项目管理部

让一切按时、在预算内推进。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎬 [工作室制片人](project-management/project-management-studio-producer.md) | 高层编排、投资组合管理 | 多项目监督、战略对齐、资源分配 |
| 🐑 [项目牧羊人](project-management/project-management-project-shepherd.md) | 跨职能协调、时间线管理 | 端到端项目协调、利益相关者管理 |
| 🧪 [实验追踪器](project-management/project-management-experiment-tracker.md) | A/B 测试、假设验证 | 实验管理、数据驱动决策 |
| 👔 [高级项目经理](project-management/project-manager-senior.md) | 现实范围界定、任务拆解 | 将规格转化为任务、范围管理 |
| 📋 [Jira 工作流管理员](project-management/project-management-jira-workflow-steward.md) | Git 工作流、分支策略、可追溯性 | 执行 Jira 关联的 Git 纪律和交付 |

### 🧪 测试部

找出问题，让用户无需遭受故障。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 📸 [证据收集者](testing/testing-evidence-collector.md) | 截图式 QA、视觉证明 | UI 测试、视觉验证、Bug 文档 |
| 🔍 [现实核查员](testing/testing-reality-checker.md) | 基于证据的认证、质量关卡 | 生产就绪性、质量审批、发布认证 |
| ⚡ [性能基准测试员](testing/testing-performance-benchmarker.md) | 性能测试、优化 | 速度测试、负载测试、性能调优 |
| 🔌 [API 测试员](testing/testing-api-tester.md) | API 验证、集成测试 | API 测试、端点验证、集成 QA |
| ♿ [无障碍审计员](testing/testing-accessibility-auditor.md) | WCAG 审计、辅助技术测试 | 无障碍合规、屏幕阅读器测试、包容性设计验证 |

### 🛟 支持部

运营的核心支柱。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 💬 [支持响应者](support/support-support-responder.md) | 客户服务、问题解决 | 客户支持、用户体验、支持运营 |
| 📊 [数据分析报告员](support/support-analytics-reporter.md) | 数据分析、仪表盘、洞察 | 商业智能、KPI 追踪、数据可视化 |
| 💰 [财务追踪员](support/support-finance-tracker.md) | 财务规划、预算管理 | 财务分析、现金流、业务绩效 |
| ⚖️ [法律合规检查员](support/support-legal-compliance-checker.md) | 合规、法规、法律审查 | 法律合规、监管要求、风险管理 |
| 📑 [执行摘要生成器](support/support-executive-summary-generator.md) | C 级沟通、战略摘要 | 高管汇报、战略沟通、决策支持 |

### 🥽 空间计算部

构建沉浸式未来。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🏗️ [XR 界面架构师](spatial-computing/xr-interface-architect.md) | 空间交互设计、沉浸式 UX | AR/VR/XR 界面设计、空间计算 UX |
| 💻 [macOS 空间/Metal 工程师](spatial-computing/macos-spatial-metal-engineer.md) | Swift、Metal、高性能 3D | macOS 空间计算、Vision Pro 原生应用 |
| 🌐 [XR 沉浸开发者](spatial-computing/xr-immersive-developer.md) | WebXR、基于浏览器的 AR/VR | 基于浏览器的沉浸式体验、WebXR 应用 |
| 🍎 [visionOS 空间工程师](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro 开发 | Vision Pro 应用、空间计算体验 |

### 🎯 专项部

不拘一格的独特专家。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎭 [智能体编排者](specialized/agents-orchestrator.md) | 多智能体协调、工作流管理 | 需要多个智能体协作的复杂项目 |
| 🔐 [智能体身份与信任架构师](specialized/agentic-identity-trust.md) | 智能体身份、认证、信任验证 | 多智能体身份系统、智能体授权、审计追踪 |
| 📋 [合规审计员](specialized/compliance-auditor.md) | SOC 2、ISO 27001、HIPAA、PCI-DSS | 引导组织通过合规认证 |
| 🌍 [文化智能策略师](specialized/specialized-cultural-intelligence-strategist.md) | 全球 UX、多元代表性、文化排斥 | 确保软件在各文化中产生共鸣 |
| 🔌 [MCP 构建者](specialized/specialized-mcp-builder.md) | Model Context Protocol 服务器、AI 智能体工具 | 构建扩展 AI 智能体能力的 MCP 服务器 |
| ⚙️ [自动化治理架构师](specialized/automation-governance-architect.md) | 自动化治理、n8n、工作流审计 | 大规模评估和治理业务自动化 |
| 🏛️ [政府数字化售前顾问](specialized/government-digital-presales-consultant.md) | 中国 ToG 售前、数字化转型 | 政府数字化转型方案和投标 |
| ⚕️ [医疗营销合规](specialized/healthcare-marketing-compliance.md) | 中国医疗广告合规 | 医疗营销监管合规 |
| 🎯 [招聘专家](specialized/recruitment-specialist.md) | 人才获取、招聘运营 | 招聘战略、寻源和招聘流程 |
| 🎓 [留学顾问](specialized/study-abroad-advisor.md) | 国际教育、申请规划 | 美国、英国、加拿大、澳大利亚留学规划 |
| 🗺️ [供应链策略师](specialized/supply-chain-strategist.md) | 供应链管理、采购策略 | 供应链优化和采购规划 |
| ☁️ [Salesforce 架构师](specialized/specialized-salesforce-architect.md) | 多云 Salesforce 设计、Governor Limits、集成 | 企业 Salesforce 架构、组织策略、部署流水线 |
| 🇰🇷 [韩国商业领航者](specialized/specialized-korean-business-navigator.md) | 韩国商业文化、品议流程、关系机制 | 在韩国商业关系中导航的外籍专业人士 |
| 🏗️ [土木工程师](specialized/specialized-civil-engineer.md) | 结构分析、岩土设计、全球建筑规范 | 基于 Eurocode、ACI、AISC 等多标准的结构工程 |

### 🎮 游戏开发部

跨主流引擎构建世界、系统和体验。

#### 跨引擎智能体（引擎无关）

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🎯 [游戏设计师](game-development/game-designer.md) | 系统设计、GDD 撰写、经济平衡、游戏循环 | 设计游戏机制、进度系统、编写设计文档 |
| 🗺️ [关卡设计师](game-development/level-designer.md) | 布局理论、节奏感、遭遇设计、环境叙事 | 建造关卡、设计遭遇流程、空间叙事 |
| 🔊 [游戏音频工程师](game-development/game-audio-engineer.md) | FMOD/Wwise、自适应音乐、空间音频、音频预算 | 交互式音频系统、动态音乐、音频性能 |
| 📖 [叙事设计师](game-development/narrative-designer.md) | 故事系统、分支对话、世界传承架构 | 编写分支叙事、实现对话系统、世界设定 |

#### Unity

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🏗️ [Unity 架构师](game-development/unity/unity-architect.md) | ScriptableObjects、数据驱动模块化、DOTS/ECS | 大型 Unity 项目、数据驱动系统设计、ECS 性能工作 |
| ✨ [Unity Shader Graph 艺术家](game-development/unity/unity-shader-graph-artist.md) | Shader Graph、HLSL、URP/HDRP、Renderer Features | 自定义 Unity 材质、特效着色器、后处理通道 |
| 🌐 [Unity 多人联网工程师](game-development/unity/unity-multiplayer-engineer.md) | Netcode for GameObjects、Unity Relay/Lobby、服务器权威、预测 | 在线 Unity 游戏、客户端预测、Unity Gaming Services 集成 |

#### Unreal Engine

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| ⚙️ [Unreal 系统工程师](game-development/unreal-engine/unreal-systems-engineer.md) | C++/Blueprint 混合、GAS、Nanite 约束、内存管理 | 复杂 Unreal 游戏系统、Gameplay Ability System、引擎级 C++ |
| 🎨 [Unreal 技术美术](game-development/unreal-engine/unreal-technical-artist.md) | Material Editor、Niagara、PCG、Substrate | Unreal 材质、Niagara 特效、程序化内容生成 |

#### Godot

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 📜 [Godot 游戏脚本师](game-development/godot/godot-gameplay-scripter.md) | GDScript 2.0、信号、组合、静态类型 | Godot 游戏系统、场景组合、高性能 GDScript |
| 🌐 [Godot 多人联网工程师](game-development/godot/godot-multiplayer-engineer.md) | MultiplayerAPI、ENet/WebRTC、RPC、权威模型 | 在线 Godot 游戏、场景复制、服务器权威 Godot |

### 📚 学术部

为世界构建、叙事和叙事设计提供学术严谨性。

| 智能体 | 专业方向 | 适用场景 |
|--------|---------|---------|
| 🌍 [人类学家](academic/academic-anthropologist.md) | 文化系统、亲属关系、仪式、信仰系统 | 设计内部逻辑连贯的文化社会 |
| 🌐 [地理学家](academic/academic-geographer.md) | 自然/人文地理、气候、制图学 | 构建地理连贯的世界，含真实的地形和聚落 |
| 📚 [历史学家](academic/academic-historian.md) | 历史分析、分期、物质文化 | 验证历史连贯性，以真实时代细节丰富场景 |
| 📜 [叙事学家](academic/academic-narratologist.md) | 叙事理论、故事结构、人物弧线 | 用成熟理论框架分析和改进故事结构 |
| 🧠 [心理学家](academic/academic-psychologist.md) | 人格理论、动机、认知模式 | 构建以研究为基础的心理可信角色 |

---

## 🎯 真实世界用例

### 场景一：构建创业 MVP

**你的团队**：
1. 🎨 **前端开发者** - 构建 React 应用
2. 🏗️ **后端架构师** - 设计 API 和数据库
3. 🚀 **增长黑客** - 规划用户获取
4. ⚡ **快速原型工程师** - 快速迭代周期
5. 🔍 **现实核查员** - 确保上线前质量

**结果**：在每个阶段都有专业知识的加持下，更快交付产品。

---

### 场景二：营销活动上线

**你的团队**：
1. 📝 **内容创作者** - 开发活动内容
2. 🐦 **Twitter 互动专家** - Twitter 策略和执行
3. 📸 **Instagram 策展人** - 视觉内容和限时动态
4. 🤝 **Reddit 社区建设者** - 真实社区互动
5. 📊 **数据分析报告员** - 追踪和优化表现

**结果**：具备平台专属专业知识的多渠道协调活动。

---

### 场景三：企业功能开发

**你的团队**：
1. 👔 **高级项目经理** - 范围界定和任务规划
2. 💎 **高级开发者** - 复杂实现
3. 🎨 **UI 设计师** - 设计系统和组件
4. 🧪 **实验追踪器** - A/B 测试规划
5. 📸 **证据收集者** - 质量验证
6. 🔍 **现实核查员** - 生产就绪性

**结果**：具备质量关卡和文档的企业级交付。

---

### 场景四：中国市场全平台运营

**你的团队**：
1. 🇨🇳 **中国市场本地化策略师** - 整体本地化战略
2. 🎵 **抖音策略师** - 短视频内容增长
3. 📕 **小红书专家** - 种草内容运营
4. 💬 **微信公众号运营** - 私域流量管理
5. 🛒 **中国电商运营** - 多平台电商

**结果**：全方位覆盖中国主要平台，实现本土化品牌增长。

---

## 🤝 贡献

欢迎贡献！以下是你可以参与的方式：

### 添加新智能体

1. Fork 本仓库
2. 在合适的分类中创建新智能体文件
3. 遵循智能体模板结构：
   - 含 name、description、color 的 frontmatter
   - 身份与记忆部分
   - 核心使命
   - 关键规则（领域专属）
   - 含示例的技术交付物
   - 工作流程
   - 成功指标
4. 提交包含智能体介绍的 PR

### 改进现有智能体

- 添加真实世界案例
- 增强代码示例
- 更新成功指标
- 改进工作流程

### 分享你的成功故事

使用过这些智能体并取得成效？在 [Discussions](https://github.com/msitarzewski/agency-agents/discussions) 中分享你的故事！

详见 [贡献指南（中文）](CONTRIBUTING_zh-CN.md)。

---

## 📖 智能体设计理念

每位智能体的设计遵循以下原则：

1. **🎭 强烈个性**：不是泛泛的模板，而是真实的角色和声音
2. **📋 明确交付物**：具体的输出成果，而非模糊的指导意见
3. **✅ 成功指标**：可量化的结果和质量标准
4. **🔄 验证过的工作流**：经过实践检验的分步流程
5. **💡 学习记忆**：模式识别与持续改进

---

## 🎁 是什么让这个项目与众不同？

### 不同于泛泛的 AI 提示词：
- ❌ 通用的"扮演开发者"提示词
- ✅ 具备个性和流程的深度专业化

### 不同于提示词库：
- ❌ 一次性提示词集合
- ✅ 配备工作流和可交付成果的完整智能体系统

### 不同于 AI 工具：
- ❌ 无法定制的黑盒工具
- ✅ 透明、可 fork、可调整的智能体个性

---

## 🔌 多工具集成

The Agency 与 Claude Code 原生兼容，并附带转换和安装脚本，让你可以在所有主流 AI 编码工具中使用相同的智能体。

### 支持的工具

- **[Claude Code](https://claude.ai/code)** — 原生 `.md` 智能体，无需转换 → `~/.claude/agents/`
- **[GitHub Copilot](https://github.com/copilot)** — 原生 `.md` 智能体，无需转换 → `~/.github/agents/`
- **[Cursor](https://cursor.sh)** — `.mdc` 规则文件 → `.cursor/rules/`
- **[Aider](https://aider.chat)** — 单一 `CONVENTIONS.md` → `./CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** — 单一 `.windsurfrules` → `./.windsurfrules`
- **[OpenCode](https://opencode.ai)** — `.md` 智能体文件 → `.opencode/agents/`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — 扩展 + `SKILL.md` 文件
- **[Kimi Code](https://github.com/MoonshotAI/kimi-cli)** — YAML 智能体规格 → `~/.config/kimi/agents/`

### ⚡ 快速安装

**第一步 —— 生成集成文件：**
```bash
./scripts/convert.sh
```

**第二步 —— 安装（交互式，自动检测你的工具）：**
```bash
./scripts/install.sh

# 或直接指定特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool kimi
```

---

## 🚀 NEXUS：多智能体编排框架

NEXUS 将单个智能体转化为协调一致的流水线，支持三种部署模式：

| 模式 | 智能体数量 | 时间线 | 适用场景 |
|------|-----------|-------|---------|
| **NEXUS-Full** | 全部 160+ | 12-24 周 | 完整产品生命周期（全部 7 个阶段） |
| **NEXUS-Sprint** | 15-25 个 | 2-6 周 | 功能/MVP 交付 |
| **NEXUS-Micro** | 5-10 个 | 1-5 天 | 针对性任务（Bug 修复、审计、活动） |

### 7 阶段 NEXUS 流水线

1. **第 0 阶段：探索** —— 市场验证、竞争分析、用户研究、法律/合规
2. **第 1 阶段：战略** —— 架构、UX 设计、品牌塑造、路线图规划
3. **第 2 阶段：基础** —— 脚手架、基础设施搭建、开发环境
4. **第 3 阶段：构建** —— 开发 ↔ QA 持续循环（构建 → 测试 → 通过/失败 → 重试）
5. **第 4 阶段：加固** —— 安全、性能、无障碍、最终 QA
6. **第 5 阶段：发布** —— 营销、增长、GTM、数据分析设置
7. **第 6 阶段：运营** —— 监控、支持、持续优化

更多详情见 [strategy/](strategy/) 目录。

---

## 📊 项目统计

- 🎭 **160+ 专业智能体**，覆盖 13 个部门
- 📝 **38,700+ 行**个性、流程和代码示例
- ⏱️ **数月迭代**，源自真实使用经验
- 🌟 **经过实战检验**，在生产环境中运行
- 🔌 **支持 11 种工具**集成格式

---

## 📄 许可证

MIT 许可证 —— 自由使用、修改和分发。

详见 [LICENSE](LICENSE)。
