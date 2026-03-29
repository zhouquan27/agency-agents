# 🎭 The Agency：随时为您效力的 AI 专家团队

> **一支完整的 AI 代理机构触手可及** —— 从前端开发向导到增长营销策略师，从游戏开发专家到品牌设计顾问。每位 Agent 都是具备独特个性、完整工作流程和成熟交付物的领域专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

[English](README.md) | 中文

---

## 🚀 这是什么？

**The Agency** 诞生于一个 Reddit 讨论帖，经过数月的迭代打磨，成为了一个持续增长的 AI Agent 个性集合库。每位 Agent 都具备：

- **🎯 深度专业化**：在各自领域拥有深厚专业知识（而非通用提示词模板）
- **🧠 独特个性**：独特的声音、沟通风格和工作方式
- **📋 交付导向**：产出真实代码、工作流程和可量化成果
- **✅ 生产就绪**：经过实战检验的工作流程和成功指标

**可以这样理解**：组建你的梦之队，只不过这些 AI 专家永不休眠、永不抱怨、始终交付。

---

## 📂 仓库结构总览

```
agency-agents/
├── README.md                   # 英文主文档
├── README.zh.md                # 中文文档（本文件）
├── CONTRIBUTING.md             # 贡献指南
├── LICENSE                     # MIT 开源协议
├── scripts/                    # 核心工具脚本
│   ├── convert.sh              # 将 Agent 转换为各工具专用格式
│   ├── install.sh              # 安装 Agent 到工具目录
│   └── lint-agents.sh          # 验证 Agent Markdown 文件格式
├── integrations/               # 各工具集成目录（自动生成）
│   ├── claude-code/
│   ├── github-copilot/
│   ├── cursor/
│   ├── aider/
│   ├── windsurf/
│   └── ...
├── academic/                   # 学术研究类 Agent（5个）
├── design/                     # 设计类 Agent（8个）
├── engineering/                # 工程技术类 Agent（26个）
├── game-development/           # 游戏开发类 Agent（20个）
├── marketing/                  # 市场营销类 Agent（29个）
├── paid-media/                 # 付费媒体类 Agent（7个）
├── product/                    # 产品管理类 Agent（5个）
├── project-management/         # 项目管理类 Agent（6个）
├── sales/                      # 销售类 Agent（8个）
├── specialized/                # 特殊专项类 Agent（28个）
├── spatial-computing/          # 空间计算类 Agent（6个）
├── strategy/                   # 战略规划类 Agent（16个）
├── support/                    # 客户支持类 Agent（6个）
└── testing/                    # 测试质量类 Agent（8个）
```

**核心数据：**
- 🤖 **201 个 Agent 文件**，覆盖 14 个专业类别
- 📜 **1,393 行** Bash 脚本自动化工具
- 🌐 **10+ 种** AI 编码平台集成支持
- 🆓 **MIT 许可证**，完全免费开源

---

## ⚡ 快速开始

### 方案一：与 Claude Code 配合使用（推荐）

```bash
# 将 Agent 复制到 Claude Code 目录
cp -r agency-agents/* ~/.claude/agents/

# 在 Claude Code 会话中激活任意 Agent：
# "嘿 Claude，切换到前端开发模式，帮我构建一个 React 组件"
```

### 方案二：自动安装脚本

```bash
# 克隆仓库
git clone https://github.com/msitarzewski/agency-agents.git
cd agency-agents

# 运行安装脚本（自动检测已安装的工具）
./scripts/install.sh

# 或指定工具安装
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
```

### 方案三：手动参考使用

直接浏览各类别目录，将 Agent 文件内容作为提示词模板使用。

---

## 🤖 Agent 分类详解

### 💻 工程技术类 (`engineering/`)

26 个专业工程 Agent，覆盖全栈开发各领域：

| Agent | 专业方向 |
|-------|---------|
| Frontend Developer | React、Vue、TypeScript 前端开发 |
| Backend Developer | Node.js、Python、微服务后端开发 |
| Full-Stack Developer | 端到端全栈解决方案 |
| DevOps Engineer | CI/CD、容器化、云基础设施 |
| Security Engineer | 安全审计、渗透测试、漏洞分析 |
| Mobile Developer | iOS/Android 跨平台移动应用 |
| Database Administrator | 数据库设计与优化 |
| API Architect | RESTful/GraphQL API 设计 |
| ... | 更多工程专项 |

### 🎨 设计类 (`design/`)

8 个专业设计 Agent：

| Agent | 专业方向 |
|-------|---------|
| UI Designer | 用户界面设计与设计系统 |
| UX Designer | 用户体验研究与交互设计 |
| Brand Designer | 品牌视觉识别系统 |
| Visual Storyteller | 视觉叙事与内容创作 |
| ... | 更多设计专项 |

### 📢 市场营销类 (`marketing/`)

29 个营销 Agent，涵盖现代营销各领域：

| Agent | 专业方向 |
|-------|---------|
| Growth Marketer | 增长黑客与转化优化 |
| Content Strategist | 内容战略与 SEO |
| Social Media Manager | 社交媒体运营与增长 |
| Email Marketer | 邮件营销与自动化 |
| ... | 更多营销专项 |

### 🎮 游戏开发类 (`game-development/`)

20 个游戏开发 Agent，支持主流引擎：

| 子目录 | 专业方向 |
|--------|---------|
| `unity/` | Unity 游戏开发 |
| `unreal-engine/` | Unreal Engine 开发 |
| `godot/` | Godot 引擎开发 |
| `roblox-studio/` | Roblox 游戏创作 |
| `blender/` | Blender 3D 建模与动画 |

### 📊 战略规划类 (`strategy/`)

16 个战略 Agent，助力商业决策：

- **协调类** (`coordination/`)：多 Agent 协作与项目协调
- **剧本类** (`playbooks/`)：标准化业务流程与操作手册
- **运行手册** (`runbooks/`)：技术操作规程与应急响应

### 🧪 测试质量类 (`testing/`)

8 个 QA 专家 Agent：单元测试、集成测试、E2E 测试、性能测试等。

### 📚 学术研究类 (`academic/`)

5 个学术 Agent：研究方法论、文献综述、人类学、心理学、历史研究等。

### 💰 付费媒体类 (`paid-media/`)

7 个付费广告 Agent：PPC、SEM、社交广告、程序化广告等。

### 💼 销售类 (`sales/`)

8 个销售 Agent：出站销售、发现通话、提案撰写、交易谈判等。

### 🌐 空间计算类 (`spatial-computing/`)

6 个 AR/VR/XR 专家 Agent。

### 🆘 客户支持类 (`support/`)

6 个支持 Agent：客户成功、运营支持、技术支持等。

### 📋 产品管理类 (`product/`)

5 个产品 Agent：冲刺规划、用户反馈、市场趋势分析等。

### 🗂️ 项目管理类 (`project-management/`)

6 个 PM Agent：敏捷教练、Scrum Master、项目协调等。

### ✨ 特殊专项类 (`specialized/`)

28 个独特专项 Agent，包括法律、财务、医疗、教育等不常见领域。

---

## 📄 Agent 文件格式

每个 Agent 都是一个遵循统一结构的 Markdown 文件：

```markdown
---
name: Agent 名称
description: 专业方向一句话描述
color: 颜色名称或十六进制代码
emoji: 🎯
vibe: 个性标语
---

# Agent 名称

## 🧠 身份与记忆
- **角色**：明确的角色定义
- **个性**：性格特征描述
- **记忆**：Agent 记住的内容
- **经验**：领域专业知识

## 🎯 核心使命
- 主要职责 1 及交付物
- 主要职责 2 及交付物

## 🚨 关键规则
领域特定的规则和约束

## 📋 技术交付物
代码示例、模板、框架、文档

## 🔄 工作流程
1. 阶段一：发现
2. 阶段二：规划
3. 阶段三：执行
4. 阶段四：审查

## 💭 沟通风格
Agent 与用户的沟通方式

## 🎯 成功指标
可量化的成果（定量和定性）
```

---

## 🔧 工具脚本说明

### `scripts/convert.sh` — 格式转换

将 Agent Markdown 文件转换为各工具专用格式：

```bash
# 转换为所有支持格式
./scripts/convert.sh

# 转换为特定工具格式
./scripts/convert.sh --tool cursor      # 生成 .mdc 规则文件
./scripts/convert.sh --tool aider       # 生成 CONVENTIONS.md
./scripts/convert.sh --tool windsurf    # 生成 .windsurfrules
./scripts/convert.sh --tool gemini-cli  # 生成扩展 + SKILL.md

# 并行转换（提升速度）
./scripts/convert.sh --parallel --jobs 8
```

### `scripts/install.sh` — 自动安装

将 Agent 安装到各工具的配置目录：

```bash
# 交互式安装（自动检测已安装工具）
./scripts/install.sh

# 安装到特定工具
./scripts/install.sh --tool claude-code  # 安装到 ~/.claude/agents/
./scripts/install.sh --tool copilot      # 安装到 ~/.github/agents/
./scripts/install.sh --tool cursor       # 安装到 .cursor/rules/
```

### `scripts/lint-agents.sh` — 格式验证

验证 Agent Markdown 文件是否符合规范：

```bash
# 验证所有 Agent
./scripts/lint-agents.sh

# 验证特定文件
./scripts/lint-agents.sh engineering/engineering-frontend-developer.md

# 成功输出示例：
# Results: 0 error(s), 0 warning(s) in 1 files.
# PASSED
```

---

## 🌐 支持的工具平台

| 工具 | 说明 | Agent 存放位置 |
|------|------|--------------|
| **Claude Code** | Anthropic AI 编码助手 | `~/.claude/agents/` |
| **GitHub Copilot** | GitHub AI 配对程序员 | `~/.github/agents/` |
| **Cursor** | AI 优先的代码编辑器 | `.cursor/rules/*.mdc` |
| **Aider** | AI 配对编程 CLI 工具 | `./CONVENTIONS.md` |
| **Windsurf** | Codeium AI IDE | `./.windsurfrules` |
| **Gemini CLI** | Google Gemini 命令行 | 扩展 + `SKILL.md` |
| **OpenCode** | 开源 AI 编码工具 | `./*.md` |
| **Kimi Code** | Kimi AI 编码助手 | YAML 规格文件 |
| **Antigravity** | AI 技能框架 | `.md` 技能文件 |
| **OpenClaw** | 工作区 AI 助手 | `SOUL.md` + `AGENTS.md` |

---

## 🤝 如何贡献

欢迎贡献新的 Agent！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细指南。

**贡献流程简述：**

1. Fork 仓库
2. 选择合适的类别目录
3. 按照模板创建新的 `.md` Agent 文件
4. 运行 linter 验证格式：`./scripts/lint-agents.sh your-agent.md`
5. 提交 Pull Request

**Agent 设计原则：**
- 赋予 Agent 独特个性，而非通用模板
- 定义清晰的交付物和可量化的成功指标
- 包含真实的工作流程和最佳实践
- 在实际场景中测试后再提交

---

## 📋 CI/CD 流程

每次提交触发自动化检查：

1. **GitHub Actions** 运行 `lint-agents.yml` 工作流
2. 自动验证所有修改的 Agent 文件格式
3. 检查必填字段（name、description、color）
4. 验证推荐章节的存在
5. 确认最低内容长度（50+ 词）

---

## 📜 开源协议

本项目采用 [MIT 许可证](LICENSE)，可自由用于个人和商业项目。

---

## 💡 使用示例

### 示例 1：前端开发场景

```
用户：帮我构建一个带有暗黑模式的 React 仪表板
Claude（激活 Frontend Developer Agent）：
  - 分析需求，确定组件架构
  - 使用 Tailwind CSS 实现主题切换
  - 提供完整的 TypeScript 代码
  - 包含无障碍访问最佳实践
  - 交付可复用的组件库
```

### 示例 2：内容营销场景

```
用户：帮我为 SaaS 产品制定内容战略
Claude（激活 Content Strategist Agent）：
  - 分析目标受众和竞争对手
  - 制定关键词研究计划
  - 设计内容日历和发布节奏
  - 提供 SEO 优化的内容模板
  - 定义内容 KPI 和追踪方法
```

### 示例 3：多 Agent 协作场景

```
用户：我需要从 0 到 1 构建一款移动应用
激活 Strategy Coordinator + Product Manager + Mobile Developer + UX Designer
  - 战略协调 Agent 制定整体路线图
  - 产品 Agent 定义功能优先级
  - UX Agent 设计用户旅程和原型
  - 移动 Agent 实现跨平台开发方案
```

---

*这份文档帮助中文用户快速理解和使用 The Agency 仓库。如有问题或建议，欢迎提交 Issue 或 Pull Request。*
