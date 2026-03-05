# Claude Code 技能手册

> 来自三个主要仓库的全面技能指南
>
> 生成日期：2026-03-04

---

## 目录

1. [概述](#概述)
2. [softaworks/agent-toolkit](#softaworksagent-toolkit)
3. [sickn33/antigravity-awesome-skills](#sickn33antigravity-awesome-skills)
4. [Yeachan-Heo/oh-my-claudecode](#yeachan-heooh-my-claudecode)
5. [parcadei/continuous-claude-v3](#parcadeicontinuous-claude-v3)
6. [快速参考](#快速参考)

---

## 概述

| 仓库 | 技能数量 | 描述 |
|------|---------|------|
| **softaworks/agent-toolkit** | 50+ | 面向开发、文档、规划和专业工作流的精品技能 |
| **sickn33/antigravity-awesome-skills** | 960+ | 适用于所有 AI 编程助手的通用技能终极集合 |
| **Yeachan-Heo/oh-my-claudecode** | 35+ 命令，21 个代理 | 零学习曲线的多代理编排系统 |
| **parcadei/continuous-claude-v3** | 109 技能，32 代理，30 钩子 | 持久化、可学习、多代理开发环境 |

---

## softaworks/agent-toolkit

**仓库**: https://github.com/softaworks/agent-toolkit

**安装**:
```bash
npx skills add softaworks/agent-toolkit
```

### AI 工具 🤖

| 技能 | 描述 |
|------|------|
| `codex` | 使用 GPT-5.2 进行高级代码分析 |
| `gemini` | 大规模代码审查（200k+ 上下文） |
| `perplexity` | 网络搜索与研究 |

### 元技能 🔮

| 技能 | 描述 |
|------|------|
| `agent-md-refactor` | 重构臃肿的代理指令文件 |
| `command-creator` | 创建 Claude Code 斜杠命令 |
| `plugin-forge` | 构建 Claude Code 插件和清单 |
| `skill-judge` | 评估技能设计质量 |

### 文档 📝

| 技能 | 描述 |
|------|------|
| `backend-to-frontend-handoff-docs` | 面向前端的 API 交接文档 |
| `c4-architecture` | 使用 Mermaid 绘制 C4 架构图 |
| `crafting-effective-readmes` | 编写高效的 README 文件 |
| `draw-io` | 创建和编辑 draw.io 图表 |
| `excalidraw` | 使用 Excalidraw 绘图 |
| `frontend-to-backend-requirements` | 记录 API 需求 |
| `marp-slide` | 专业演示幻灯片 |
| `mermaid-diagrams` | 使用 Mermaid 绘制软件图表 |
| `writing-clearly-and-concisely` | 清晰、专业的写作 |

### 设计与前端 🎨

| 技能 | 描述 |
|------|------|
| `design-system-starter` | 创建设计系统 |
| `mui` | Material-UI v7 模式 |
| `openapi-to-typescript` | 将 OpenAPI 转换为 TypeScript |
| `react-dev` | 使用 TypeScript 的类型安全 React 18-19 |
| `react-useeffect` | React useEffect 最佳实践 |

### 开发 🛠️

| 技能 | 描述 |
|------|------|
| `database-schema-designer` | 设计健壮的数据库模式 |
| `dependency-updater` | 智能依赖管理 |
| `naming-analyzer` | 建议更好的变量/函数名 |
| `lesson-learned` | 从最近的代码变更中提取经验教训 |
| `reducing-entropy` | 最小化代码库规模 |
| `session-handoff` | 无缝 AI 会话交接 |

### 规划 🎯

| 技能 | 描述 |
|------|------|
| `game-changing-features` | 发现 10 倍产品机会 |
| `gepetto` | 详细的实现规划 |
| `requirements-clarity` | 编码前澄清需求 |
| `ship-learn-next` | 将学习转化为可执行的任务 |

### 职业素养 👔

| 技能 | 描述 |
|------|------|
| `daily-meeting-update` | 交互式每日站会生成器 |
| `difficult-workplace-conversations` | 处理困难的职场对话 |
| `feedback-mastery` | 提供建设性反馈 |
| `professional-communication` | 技术沟通指南 |

### 测试 🧪

| 技能 | 描述 |
|------|------|
| `qa-test-planner` | 全面的 QA 测试规划 |

### Git 📦

| 技能 | 描述 |
|------|------|
| `commit-work` | 高质量的 git 提交 |

### 实用工具 🔧

| 技能 | 描述 |
|------|------|
| `datadog-cli` | 使用 Datadog 日志和指标进行调试 |
| `domain-name-brainstormer` | 生成和检查域名 |
| `humanizer` | 移除 AI 写作模式 |
| `meme-factory` | 使用 API 生成梗图 |
| `jira` | 自然语言与 Jira 交互 |
| `web-to-markdown` | 将网页转换为 Markdown |

### 代理 (Agents)

| 代理 | 描述 |
|------|------|
| `ascii-ui-mockup-generator` | 通过 ASCII 草图可视化 UI 概念 |
| `codebase-pattern-finder` | 查找相似实现和模式 |
| `communication-excellence-coach` | 邮件优化、语气校准、角色扮演 |
| `general-purpose` | 用于复杂多步骤任务的默认代理 |
| `mermaid-diagram-specialist` | 创建流程图、序列图、ERD |
| `ui-ux-designer` | 基于研究的 UI/UX 设计反馈 |

### 斜杠命令 (Slash Commands)

| 命令 | 描述 |
|------|------|
| `/codex-plan` | 使用 Codex 5.2 创建实现计划 |
| `/compose-email` | 起草专业邮件 |
| `/explain-changes-mental-model` | 建立代码变更的心智模型 |
| `/explain-pr-changes` | 生成 PR 摘要 |
| `/sync-branch` | 同步特性分支与主分支 |
| `/sync-skills-readme` | 更新 README 技能表 |
| `/viral-tweet` | 优化推文创意以提高 X 互动率 |

---

## sickn33/antigravity-awesome-skills

**仓库**: https://github.com/sickn33/antigravity-awesome-skills

**技能总数**: 960+

**安装**:
```bash
npx skills add sickn33/antigravity-awesome-skills
```

### 架构 (Architecture)
系统设计、ADRs、C4 和可扩展模式

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `architecture` | 架构决策框架 | 提供架构决策制定框架，用于需求分析和权衡评估，记录架构决策理由。 |
| `c4-context` | C4 上下文图 | 创建系统上下文图，展示系统与外部用户/系统的关系。 |
| `senior-architect` | 资深架构师 | 提供高级系统架构设计指导，包括技术选型和可扩展模式。 |
| `architecture-decision-records` | 架构决策记录 | 创建和维护架构决策记录（ADR），捕获重要技术决策的背景和理由。 |
| `architecture-patterns` | 架构模式 | 提供常用架构模式的参考和选择指南，包括决策树和反模式。 |
| `monorepo-architect` | 单体仓库架构师 | 设计和维护 monorepo 项目结构，管理多项目的依赖和构建。 |
| `c4-code` | C4 代码图 | 从源代码生成 C4 代码级可视化图，展示类和组件关系。 |
| `c4-component` | C4 组件图 | 创建组件级 C4 图，展示系统内部组件及其交互关系。 |
| `c4-container` | C4 容器图 | 创建容器级 C4 图，展示应用程序、数据存储和微服务容器。 |
| `ddd-context-mapping` | DDD 上下文映射 | 定义领域驱动设计中不同界限上下文之间的映射关系。 |
| `ddd-strategic-design` | DDD 战略设计 | 实施领域驱动设计的战略模式，包括界限上下文和通用语言。 |
| `ddd-tactical-patterns` | DDD 战术模式 | 提供领域驱动设计的战术实现模式，如聚合根和领域服务。 |
| `domain-driven-design` | 领域驱动设计 | 应用 DDD 原则进行软件设计，聚焦业务领域建模和通用语言。 |
| `software-architecture` | 软件架构 | 提供全面的软件架构设计指导，包括质量属性和架构风格。 |
| `backend-architect` | 后端架构师 | 设计后端系统架构，包括 API、数据库和分布式系统模式。 |

### 商业 (Business)
增长、定价、CRO、SEO 和上市策略

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `copywriting` | 文案写作 | 撰写有说服力的营销文案，提高转化率和用户参与度。 |
| `pricing-strategy` | 定价策略 | 设计和优化产品定价模型，平衡收益与市场竞争力。 |
| `seo-audit` | SEO 审计 | 全面审计网站 SEO 表现，识别优化机会和技术问题。 |
| `seo-content-auditor` | SEO 内容审计师 | 审查内容的 SEO 质量，提供关键词优化和内容改进建议。 |
| `seo-content-planner` | SEO 内容规划师 | 制定基于关键词研究的内容策略和发布计划。 |
| `seo-content-writer` | SEO 内容写手 | 创建 SEO 优化的内容，平衡可读性和搜索引擎排名。 |
| `seo-keyword-strategist` | SEO 关键词策略师 | 研究和选择目标关键词，制定关键词竞争策略。 |
| `seo-meta-optimizer` | SEO 元标签优化器 | 优化页面元标签（标题、描述），提高点击率和排名。 |
| `startup-business-analyst-business-case` | 初创业务分析师 - 商业案例 | 分析和编写初创企业的商业案例，评估市场可行性。 |
| `startup-business-analyst-financial-projections` | 初创业务分析师 - 财务预测 | 建立财务预测模型，估算收入、成本和现金流。 |
| `startup-business-analyst-market-opportunity` | 初创业务分析师 - 市场机会 | 评估市场机会规模，分析目标客户群体和市场趋势。 |
| `startup-financial-modeling` | 初创财务建模 | 创建详细的财务模型，支持融资和战略规划决策。 |
| `startup-metrics-framework` | 初创指标框架 | 定义和跟踪关键业务指标，如 LTV、CAC 和留存率。 |
| `marketing-psychology` | 营销心理学 | 应用心理学原理设计营销策略，影响用户决策行为。 |
| `launch-strategy` | 发布策略 | 规划产品发布活动，包括时机、渠道和推广策略。 |
| `market-sizing-analysis` | 市场规模分析 | 估算目标市场的总体规模（TAM/SAM/SOM）。 |
| `competitive-landscape` | 竞争格局分析 | 分析市场竞争态势，识别主要竞争对手和市场定位。 |
| `competitor-alternatives` | 竞争对手替代方案 | 研究竞争对手的替代产品，分析差异化和竞争优势。 |
| `culture-index` | 文化指数 | 评估和建设组织文化，测量员工参与度和价值观契合度。 |
| `hr-pro` | 人力资源专家 | 提供人力资源管理专业支持，包括招聘、绩效和员工关系。 |
| `customer-support` | 客户支持 | 设计和优化客户支持流程，提高客户满意度和留存率。 |

### 数据与 AI (Data & AI)
LLM 应用、RAG、代理、可观测性、分析

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `rag-engineer` | RAG 工程师 | 构建检索增强生成（RAG）系统，将外部知识库与 LLM 结合以提高回答准确性。 |
| `prompt-engineer` | 提示工程师 | 设计和优化提示词以获得更好的 LLM 输出效果。 |
| `langgraph` | LangGraph 架构师 | 使用 LangGraph 构建基于图的 LLM 应用和工作流。 |
| `ai-agent-development` | AI 代理开发 | 开发自主 AI 代理以执行复杂任务。 |
| `ai-agents-architect` | AI 代理架构师 | 设计 AI 代理系统的整体架构和交互模式。 |
| `ai-engineer` | AI 工程师 | 开发和部署 AI 驱动的应用和系统。 |
| `ai-ml` | AI/ML 专家 | 机器学习和人工智能技术的综合应用。 |
| `autonomous-agent-patterns` | 自主代理模式 | 实现自主 AI 代理的常见设计模式和最佳实践。 |
| `autonomous-agents` | 自主代理 | 构建能够独立执行任务的自主 AI 系统。 |
| `multi-agent-patterns` | 多代理模式 | 设计和协调多个 AI 代理协作完成任务的模式。 |
| `agent-memory-systems` | 代理记忆系统 | 为 AI 代理实现持久化和上下文记忆能力。 |
| `agent-orchestration-improve-agent` | 代理编排与改进 | 优化和改进现有 AI 代理的性能和行为。 |
| `agent-orchestration-multi-agent-optimize` | 多代理优化编排 | 优化多代理系统的协作效率和资源利用。 |
| `agent-tool-builder` | 代理工具构建师 | 为 AI 代理创建和集成外部工具和 API。 |
| `crewai` | CrewAI 专家 | 使用 CrewAI 框架编排多代理工作流。 |
| `langchain-architecture` | LangChain 架构师 | 基于 LangChain 构建 LLM 应用的架构设计。 |
| `llm-app-patterns` | LLM 应用模式 | 大语言模型应用的最佳实践和设计模式。 |
| `llm-application-dev-ai-assistant` | LLM 应用开发 - AI 助手 | 开发基于 LLM 的 AI 助手应用。 |
| `llm-application-dev-langchain-agent` | LLM 应用开发 - LangChain 代理 | 使用 LangChain 构建 LLM 代理应用。 |
| `llm-application-dev-prompt-optimize` | LLM 应用开发 - 提示优化 | 优化 LLM 应用的提示工程策略。 |
| `llm-evaluation` | LLM 评估 | 评估 LLM 模型的准确性、安全性和性能。 |
| `mlops-engineer` | MLOps 工程师 | 实现机器学习模型的部署、监控和持续集成。 |
| `ml-engineer` | ML 工程师 | 构建和优化机器学习模型和系统。 |
| `ml-pipeline-workflow` | ML 流水线工作流 | 设计和实现机器学习数据处理流水线。 |
| `machine-learning-ops-ml-pipeline` | 机器学习运维流水线 | 构建自动化 ML 训练、部署和监控流水线。 |
| `data-scientist` | 数据科学家 | 运用统计学和机器学习从数据中提取洞察。 |
| `data-engineer` | 数据工程师 | 构建和维护数据处理基础设施和流水线。 |
| `data-engineering-data-driven-feature` | 数据工程 - 数据驱动特征 | 基于数据分析构建机器学习特征工程。 |
| `data-engineering-data-pipeline` | 数据工程 - 数据流水线 | 设计大规模数据处理和 ETL 流水线。 |
| `data-quality-frameworks` | 数据质量框架 | 实施数据质量监控和验证框架。 |
| `analytics-tracking` | 分析追踪 | 实施用户行为追踪和分析系统。 |
| `amplitude-automation` | Amplitude 自动化 | 自动化 Amplitude 产品分析的配置和报告。 |
| `datadog-automation` | Datadog 自动化 | 自动化 Datadog 监控和日志分析任务。 |
| `posthog-automation` | PostHog 自动化 | 自动化 PostHog 产品分析和用户追踪。 |
| `segment-automation` | Segment 自动化 | 自动化 Segment 客户数据平台集成。 |
| `mixpanel-automation` | Mixpanel 自动化 | 自动化 Mixpanel 用户分析和事件追踪。 |

### 开发 (Development)
语言精通、框架模式、代码质量

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `typescript-expert` | TypeScript 专家 | 提供 TypeScript 语言的高级指导和最佳实践。 |
| `typescript-pro` | TypeScript 专业 | 专业的 TypeScript 开发技能，涵盖高级用法。 |
| `typescript-advanced-types` | TypeScript 高级类型 | 掌握 TypeScript 高级类型系统和类型技巧。 |
| `typescript-scaffold` | TypeScript 脚手架 | 快速搭建 TypeScript 项目结构。 |
| `javascript-pro` | JavaScript 专业 | 专业的 JavaScript 开发技能和最佳实践。 |
| `javascript-mastery` | JavaScript 精通 | 深入掌握 JavaScript 核心概念和高级特性。 |
| `javascript-testing-patterns` | JavaScript 测试模式 | JavaScript 单元测试和集成测试的最佳实践。 |
| `modern-javascript-patterns` | 现代 JavaScript 模式 | ES6+ 现代 JavaScript 编程模式和最佳实践。 |
| `react-best-practices` | React 最佳实践 | React 开发的最佳实践和代码规范。 |
| `react-patterns` | React 模式 | 常见的 React 组件模式和设计模式。 |
| `react-ui-patterns` | React UI 模式 | React 用户界面组件的设计模式。 |
| `react-state-management` | React 状态管理 | React 应用状态管理的各种方案和最佳实践。 |
| `react-nextjs-development` | React Next.js 开发 | 使用 Next.js 进行 React 全栈开发。 |
| `react-modernization` | React 现代化 | 将传统 React 代码迁移到现代最佳实践。 |
| `react-native-architecture` | React Native 架构 | React Native 移动应用的架构设计。 |
| `react-flow-architect` | React Flow 架构师 | 使用 React Flow 构建节点流程图应用。 |
| `react-flow-node-ts` | React Flow 节点 TypeScript | 使用 TypeScript 开发 React Flow 自定义节点。 |
| `nextjs-best-practices` | Next.js 最佳实践 | Next.js 框架开发的最佳实践。 |
| `nextjs-app-router-patterns` | Next.js App Router 模式 | Next.js App Router 的路由和布局模式。 |
| `nextjs-supabase-auth` | Next.js Supabase 认证 | 集成 Next.js 和 Supabase 实现用户认证。 |
| `angular` | Angular | Angular 框架的基础和高级开发技能。 |
| `angular-best-practices` | Angular 最佳实践 | Angular 开发的最佳实践和代码规范。 |
| `angular-migration` | Angular 迁移 | Angular 版本升级和项目迁移指导。 |
| `angular-state-management` | Angular 状态管理 | Angular 应用的状态管理方案（如 NgRx）。 |
| `angular-ui-patterns` | Angular UI 模式 | Angular 用户界面组件的设计模式。 |
| `vue-expert` | Vue 专家 | Vue.js 框架的高级开发和最佳实践。 |
| `nodejs-backend-patterns` | Node.js 后端模式 | Node.js 后端开发的架构模式。 |
| `nodejs-best-practices` | Node.js 最佳实践 | Node.js 开发的最佳实践和性能优化。 |
| `nestjs-expert` | NestJS 专家 | NestJS 框架的高级开发和架构设计。 |
| `python-pro` | Python 专业 | 专业的 Python 开发技能和最佳实践。 |
| `python-patterns` | Python 模式 | Python 编程的常见模式和惯用写法。 |
| `python-fastapi-development` | Python FastAPI 开发 | 使用 FastAPI 构建高性能 API。 |
| `fastapi-pro` | FastAPI 专业 | FastAPI 框架的高级用法和最佳实践。 |
| `python-testing-patterns` | Python 测试模式 | Python 单元测试和集成测试的最佳实践。 |
| `python-performance-optimization` | Python 性能优化 | Python 代码性能分析和优化技术。 |
| `golang-pro` | Go 专业 | 专业的 Go 语言开发技能和最佳实践。 |
| `go-concurrency-patterns` | Go 并发模式 | Go 语言并发编程的常见模式和最佳实践。 |
| `rust-pro` | Rust 专业 | 专业的 Rust 语言开发技能和最佳实践。 |
| `rust-async-patterns` | Rust 异步模式 | Rust 异步编程的常见模式和最佳实践。 |
| `java-pro` | Java 专业 | 专业的 Java 开发技能和最佳实践。 |
| `kotlin-coroutines-expert` | Kotlin 协程专家 | Kotlin 协程异步编程的高级用法。 |
| `scala-pro` | Scala 专业 | 专业的 Scala 函数式编程技能。 |
| `cpp-pro` | C++ 专业 | 专业的 C++ 开发技能和最佳实践。 |
| `c-pro` | C 专业 | 专业的 C 语言开发技能。 |
| `csharp-pro` | C# 专业 | 专业的 C# 开发技能和最佳实践。 |
| `dotnet-backend` | .NET 后端 | .NET 后端应用开发。 |
| `dotnet-backend-patterns` | .NET 后端模式 | .NET 后端开发的架构模式。 |
| `dotnet-architect` | .NET 架构师 | .NET 系统架构设计和规划。 |
| `ruby-pro` | Ruby 专业 | 专业的 Ruby 开发技能和最佳实践。 |
| `laravel-expert` | Laravel 专家 | Laravel PHP 框架的高级开发技能。 |
| `django-pro` | Django 专业 | Django Python 框架的专业开发技能。 |
| `elixir-pro` | Elixir 专业 | 专业的 Elixir 函数式编程技能。 |
| `php-pro` | PHP 专业 | 专业的 PHP 开发技能和最佳实践。 |
| `haskell-pro` | Haskell 专业 | 专业的 Haskell 纯函数式编程技能。 |
| `julia-pro` | Julia 专业 | 专业的 Julia 科学计算编程技能。 |
| `bun-development` | Bun 开发 | 使用 Bun 运行时进行 JavaScript/TypeScript 开发。 |
| `frontend-developer` | 前端开发者 | 前端开发的综合技能和最佳实践。 |
| `frontend-dev-guidelines` | 前端开发指南 | 前端开发的指导原则和规范。 |
| `backend-dev-guidelines` | 后端开发指南 | 后端开发的指导原则和规范。 |
| `backend-development-feature-development` | 后端功能开发 | 后端功能模块的开发流程。 |
| `mobile-developer` | 移动开发者 | 移动应用开发的综合技能。 |
| `ios-developer` | iOS 开发者 | iOS 应用开发技能（Swift/SwiftUI）。 |
| `android-jetpack-compose-expert` | Android Jetpack Compose 专家 | 使用 Jetpack Compose 开发现代 Android UI。 |
| `flutter-expert` | Flutter 专家 | Flutter 跨平台移动应用开发。 |
| `unity-developer` | Unity 开发者 | Unity 游戏引擎开发技能。 |
| `unity-ecs-patterns` | Unity ECS 模式 | Unity ECS（实体组件系统）架构模式。 |
| `unreal-engine-cpp-pro` | Unreal Engine C++ 专业 | Unreal Engine C++ 游戏开发。 |
| `godot-4-migration` | Godot 4 迁移 | 迁移到 Godot 4 引擎的指导。 |
| `godot-gdscript-patterns` | Godot GDScript 模式 | Godot GDScript 编程模式。 |
| `bevy-ecs-expert` | Bevy ECS 专家 | Bevy 引擎 ECS 架构开发。 |
| `threejs-skills` | Three.js 技能 | Three.js 3D Web 图形开发。 |
| `shader-programming-glsl` | 着色器编程 GLSL | GLSL 着色器语言编程技能。 |
| `tailwind-patterns` | Tailwind 模式 | Tailwind CSS 实用类模式和最佳实践。 |
| `tailwind-design-system` | Tailwind 设计系统 | 使用 Tailwind CSS 构建设计系统。 |
| `mui` | MUI | Material-UI React 组件库开发。 |
| `radix-ui-design-system` | Radix UI 设计系统 | 使用 Radix UI 原语构建设计系统。 |
| `design-system-starter` | 设计系统启动器 | 创建设计系统的基础框架。 |
| `clean-code` | 整洁代码 | 编写清晰、可维护代码的原则。 |
| `code-refactoring-refactor-clean` | 代码重构 - 清理 | 重构代码以提高可读性和可维护性。 |
| `code-refactoring-tech-debt` | 代码重构 - 技术债务 | 识别和解决技术债务的重构策略。 |
| `code-reviewer` | 代码审查员 | 代码审查的基本技能。 |
| `code-review-excellence` | 卓越代码审查 | 高质量的代码审查实践。 |
| `code-review-checklist` | 代码审查清单 | 代码审查的检查清单。 |
| `comprehensive-review-full-review` | 全面审查 - 完整审查 | 完整的代码审查流程。 |
| `comprehensive-review-pr-enhance` | 全面审查 - PR 增强 | 增强拉取请求质量的审查。 |
| `codebase-cleanup-refactor-clean` | 代码库清理 - 重构清理 | 代码库重构和清理。 |
| `codebase-cleanup-tech-debt` | 代码库清理 - 技术债务 | 消除代码库中的技术债务。 |
| `codebase-cleanup-deps-audit` | 代码库清理 - 依赖审计 | 代码库依赖项审计和清理。 |
| `dependency-management-deps-audit` | 依赖管理 - 依赖审计 | 项目依赖项的审计和管理。 |
| `dependency-upgrade` | 依赖升级 | 项目依赖项升级策略。 |
| `naming-analyzer` | 命名分析器 | 分析和改进变量、函数命名。 |
| `reducing-entropy` | 降低熵值 | 减少代码库复杂度和混乱度。 |
| `sharp-edges` | 尖锐边缘 | 识别代码库中容易出问题的地方。 |
| `find-bugs` | 查找缺陷 | 发现和定位代码中的 bug。 |
| `vibe-code-auditor` | Vibe 代码审计 | 快速代码审计和 vibes 检查。 |
| `production-code-audit` | 生产代码审计 | 生产环境代码的全面审计。 |

### 通用 (General)
规划、文档、产品运营、写作、指南

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `brainstorming` | 头脑风暴 | 引导创意发散思维，生成大量创新想法和解决方案。 |
| `doc-coauthoring` | 文档协作创作 | 协作文档编写，提供实时反馈和内容改进建议。 |
| `writing-plans` | 写作计划 | 制定写作计划和大纲，组织内容结构和写作流程。 |
| `plan-writing` | 计划撰写 | 编写详细的执行计划，包括目标、步骤和时间表。 |
| `writing-skills` | 写作技巧 | 提供专业写作技巧指导，包括结构、风格和表达。 |
| `documentation` | 文档编写 | 创建高质量的技术文档，包括 API 文档和用户指南。 |
| `documentation-templates` | 文档模板 | 提供标准化的文档模板，确保文档格式和结构一致。 |
| `documentation-generation-doc-generate` | 文档生成器 | 自动从代码生成文档，减少手动维护成本。 |
| `writing-clearly-and-concisely` | 清晰简洁写作 | 指导如何用简洁的语言表达复杂概念，提高可读性。 |
| `crafting-effective-readmes` | 编写高效 README | 创建引人入胜的项目 README，清晰传达项目价值。 |
| `readme` | README 文档专家 | 专注于编写专业的项目说明文档，包括安装和使用指南。 |
| `api-documentation` | API 文档 | 编写全面的 API 文档，包括端点说明、参数和示例。 |
| `api-documentation-generator` | API 文档生成器 | 自动从代码注释生成 API 参考文档。 |
| `api-documenter` | API 文档编写者 | 专业编写 API 文档，确保准确性和完整性。 |
| `professional-communication` | 专业沟通 | 提供职场专业沟通指导，包括邮件、报告和演示。 |
| `internal-comms-anthropic` | 内部沟通 - Anthropic | Anthropic 公司内部沟通最佳实践和模板。 |
| `internal-comms-community` | 内部沟通 - 社区 | 社区内部沟通指南，促进团队协作和信息共享。 |
| `content-creator` | 内容创作者 | 创建各类数字内容，包括博客、社交媒体和视频脚本。 |
| `content-marketer` | 内容营销专家 | 制定内容营销策略，通过有价值的内容吸引和转化客户。 |
| `product-marketing-context` | 产品营销背景 | 提供产品营销的背景信息和定位策略框架。 |
| `office-productivity` | 办公效率 | 提升办公效率的技巧和工具，优化日常工作流程。 |
| `file-organizer` | 文件整理专家 | 组织和管理文件和目录结构，提高工作效率。 |
| `beautiful-prose` | 优美散文 | 润色文字使其更加优美流畅，提升文学品质。 |
| `copy-editing` | 文案编辑 | 校对和编辑文案，纠正语法错误并改进表达清晰度。 |

### 基础设施 (Infrastructure)
DevOps、云、无服务器、部署、CI/CD

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `docker-expert` | Docker 专家 | 精通 Docker 容器化技术，包括镜像构建、容器编排和最佳实践。 |
| `kubernetes-architect` | Kubernetes 架构师 | 设计 Kubernetes 集群架构，包括节点规划、网络设计和资源管理策略。 |
| `kubernetes-deployment` | Kubernetes 部署 | 管理 Kubernetes 应用部署，包括 Deployment、StatefulSet 和 DaemonSet 配置。 |
| `kubernetes-specialist` | Kubernetes 专家 | 全面的 Kubernetes 运维和管理能力，涵盖集群配置、故障排除和性能优化。 |
| `helm-chart-scaffolding` | Helm Chart 脚手架 | 创建和初始化 Helm Charts，用于 Kubernetes 应用的打包和部署。 |
| `terraform-specialist` | Terraform 专家 | 精通 Terraform 基础设施即代码 (IaC)，包括状态管理和模块化设计。 |
| `terraform-infrastructure` | Terraform 基础设施 | 使用 Terraform 定义和 provision 云基础设施资源。 |
| `terraform-module-library` | Terraform 模块库 | 构建可复用的 Terraform 模块库，提高基础设施代码的复用性。 |
| `terraform-aws-modules` | Terraform AWS 模块 | 使用 Terraform AWS 官方模块快速构建 AWS 基础设施。 |
| `terraform-skill` | Terraform 技能 | 通用的 Terraform 基础设施即代码能力。 |
| `cdk-patterns` | CDK 模式 | AWS CDK (Cloud Development Kit) 最佳实践和架构模式。 |
| `cloudformation-best-practices` | CloudFormation 最佳实践 | AWS CloudFormation 模板设计和部署的最佳实践。 |
| `aws-serverless` | AWS 无服务器 | 构建 AWS Lambda、API Gateway 等无服务器应用架构。 |
| `aws-skills` | AWS 技能 | 全面的 AWS 云服务使用能力，涵盖计算、存储、网络等核心服务。 |
| `aws-cost-optimizer` | AWS 成本优化 | 分析和优化 AWS 资源使用成本，提供成本节省建议。 |
| `aws-cost-cleanup` | AWS 成本清理 | 识别和清理未使用的 AWS 资源以减少不必要的开支。 |
| `aws-penetration-testing` | AWS 渗透测试 | 对 AWS 云环境进行安全渗透测试和漏洞评估。 |
| `gcp-cloud-run` | GCP Cloud Run | 在 Google Cloud Platform 上部署和管理 Cloud Run 无服务器容器服务。 |
| `azure-functions` | Azure Functions | 开发 Azure Functions 无服务器计算应用，支持多种编程语言。 |
| `azure-identity-py` | Azure Identity (Python) | 在 Python 应用中实现 Azure 身份认证和凭证管理。 |
| `azure-identity-java` | Azure Identity (Java) | 在 Java 应用中实现 Azure 身份认证和凭证管理。 |
| `azure-identity-dotnet` | Azure Identity (.NET) | 在 .NET 应用中实现 Azure 身份认证和凭证管理。 |
| `azure-identity-ts` | Azure Identity (TypeScript) | 在 TypeScript 应用中实现 Azure 身份认证和凭证管理。 |
| `azure-identity-rust` | Azure Identity (Rust) | 在 Rust 应用中实现 Azure 身份认证和凭证管理。 |
| `azure-keyvault-py` | Azure Key Vault (Python) | 在 Python 应用中集成 Azure Key Vault 管理密钥和机密。 |
| `azure-keyvault-keys-ts` | Azure Key Vault 密钥 (TypeScript) | 在 TypeScript 应用中使用 Azure Key Vault 管理加密密钥。 |
| `azure-keyvault-keys-rust` | Azure Key Vault 密钥 (Rust) | 在 Rust 应用中使用 Azure Key Vault 管理加密密钥。 |
| `azure-keyvault-secrets-ts` | Azure Key Vault 机密 (TypeScript) | 在 TypeScript 应用中使用 Azure Key Vault 管理敏感机密。 |
| `azure-keyvault-secrets-rust` | Azure Key Vault 机密 (Rust) | 在 Rust 应用中使用 Azure Key Vault 管理敏感机密。 |
| `azure-keyvault-certificates-rust` | Azure Key Vault 证书 (Rust) | 在 Rust 应用中使用 Azure Key Vault 管理 SSL/TLS 证书。 |
| `azure-storage-blob-py` | Azure Blob 存储 (Python) | 在 Python 应用中访问和管理 Azure Blob 存储对象。 |
| `azure-storage-blob-java` | Azure Blob 存储 (Java) | 在 Java 应用中访问和管理 Azure Blob 存储对象。 |
| `azure-storage-blob-rust` | Azure Blob 存储 (Rust) | 在 Rust 应用中访问和管理 Azure Blob 存储对象。 |
| `azure-storage-blob-ts` | Azure Blob 存储 (TypeScript) | 在 TypeScript 应用中访问和管理 Azure Blob 存储对象。 |
| `azure-cosmos-py` | Azure Cosmos DB (Python) | 在 Python 应用中连接和操作 Azure Cosmos DB 多模型数据库。 |
| `azure-cosmos-java` | Azure Cosmos DB (Java) | 在 Java 应用中连接和操作 Azure Cosmos DB 多模型数据库。 |
| `azure-cosmos-db-py` | Azure Cosmos DB (Python) | 在 Python 应用中使用 Azure Cosmos DB 进行全球分布式数据管理。 |
| `azure-cosmos-rust` | Azure Cosmos DB (Rust) | 在 Rust 应用中连接和操作 Azure Cosmos DB 多模型数据库。 |
| `azure-cosmos-ts` | Azure Cosmos DB (TypeScript) | 在 TypeScript 应用中连接和操作 Azure Cosmos DB 多模型数据库。 |
| `azure-servicebus-dotnet` | Azure Service Bus (.NET) | 在 .NET 应用中使用 Azure Service Bus 进行消息传递和队列管理。 |
| `azure-servicebus-py` | Azure Service Bus (Python) | 在 Python 应用中使用 Azure Service Bus 进行消息传递和队列管理。 |
| `azure-servicebus-ts` | Azure Service Bus (TypeScript) | 在 TypeScript 应用中使用 Azure Service Bus 进行消息传递和队列管理。 |
| `azure-eventhub-dotnet` | Azure Event Hubs (.NET) | 在 .NET 应用中使用 Azure Event Hubs 进行流式事件数据采集。 |
| `azure-eventhub-java` | Azure Event Hubs (Java) | 在 Java 应用中使用 Azure Event Hubs 进行流式事件数据采集。 |
| `azure-eventhub-py` | Azure Event Hubs (Python) | 在 Python 应用中使用 Azure Event Hubs 进行流式事件数据采集。 |
| `azure-eventhub-rust` | Azure Event Hubs (Rust) | 在 Rust 应用中使用 Azure Event Hubs 进行流式事件数据采集。 |
| `azure-eventhub-ts` | Azure Event Hubs (TypeScript) | 在 TypeScript 应用中使用 Azure Event Hubs 进行流式事件数据采集。 |
| `azure-eventgrid-dotnet` | Azure Event Grid (.NET) | 在 .NET 应用中使用 Azure Event Grid 进行事件路由和分发。 |
| `azure-eventgrid-java` | Azure Event Grid (Java) | 在 Java 应用中使用 Azure Event Grid 进行事件路由和分发。 |
| `azure-eventgrid-py` | Azure Event Grid (Python) | 在 Python 应用中使用 Azure Event Grid 进行事件路由和分发。 |
| `azure-search-documents-dotnet` | Azure AI Search (.NET) | 在 .NET 应用中集成 Azure AI Search 进行全文搜索和向量检索。 |
| `azure-search-documents-py` | Azure AI Search (Python) | 在 Python 应用中集成 Azure AI Search 进行全文搜索和向量检索。 |
| `azure-search-documents-ts` | Azure AI Search (TypeScript) | 在 TypeScript 应用中集成 Azure AI Search 进行全文搜索和向量检索。 |
| `azure-monitor-opentelemetry-py` | Azure Monitor OpenTelemetry (Python) | 在 Python 应用中使用 OpenTelemetry 集成 Azure Monitor 进行可观测性监控。 |
| `azure-monitor-opentelemetry-exporter-py` | Azure Monitor OpenTelemetry 导出器 (Python) | 在 Python 应用中配置 OpenTelemetry 数据导出到 Azure Monitor。 |
| `azure-monitor-opentelemetry-exporter-java` | Azure Monitor OpenTelemetry 导出器 (Java) | 在 Java 应用中配置 OpenTelemetry 数据导出到 Azure Monitor。 |
| `azure-monitor-opentelemetry-ts` | Azure Monitor OpenTelemetry (TypeScript) | 在 TypeScript 应用中使用 OpenTelemetry 集成 Azure Monitor 进行可观测性监控。 |
| `azure-ai-openai-dotnet` | Azure AI OpenAI (.NET) | 在 .NET 应用中集成 Azure OpenAI Service 进行 AI 功能开发。 |
| `azure-ai-ml-py` | Azure AI ML (Python) | 在 Python 应用中使用 Azure AI Studio 和机器学习服务。 |
| `azure-ai-projects-dotnet` | Azure AI 项目 (.NET) | 在 .NET 应用中管理 Azure AI 项目和资源。 |
| `azure-ai-projects-java` | Azure AI 项目 (Java) | 在 Java 应用中管理 Azure AI 项目和资源。 |
| `azure-ai-projects-py` | Azure AI 项目 (Python) | 在 Python 应用中管理 Azure AI 项目和资源。 |
| `azure-ai-projects-ts` | Azure AI 项目 (TypeScript) | 在 TypeScript 应用中管理 Azure AI 项目和资源。 |
| `vercel-deployment` | Vercel 部署 | 将前端和全栈应用部署到 Vercel 平台，支持 Next.js 等框架。 |
| `vercel-automation` | Vercel 自动化 | 使用 Vercel API 和 CLI 自动化部署和项目管理工作流。 |
| `cloudflare-workers-expert` | Cloudflare Workers 专家 | 开发和部署 Cloudflare Workers 边缘计算应用，支持多种运行时。 |
| `cloud-architect` | 云架构师 | 设计多云和混合云架构，包括服务选型、成本优化和高可用性设计。 |
| `cloud-devops` | 云 DevOps | 实施云原生 DevOps 实践，包括 CI/CD、自动化运维和监控。 |
| `devops-troubleshooter` | DevOps 故障排除 | 诊断和解决 DevOps 流水线、部署和基础设施问题。 |
| `deployment-engineer` | 部署工程师 | 设计和实施应用部署策略，确保可靠和高效的发布流程。 |
| `deployment-pipeline-design` | 部署流水线设计 | 设计 CI/CD 部署流水线，实现自动化构建、测试和发布。 |
| `deployment-procedures` | 部署流程 | 制定标准化的部署操作程序和回滚策略。 |
| `deployment-validation-config-validate` | 部署验证 | 验证部署配置的正确性和完整性，确保部署成功。 |
| `gitops-workflow` | GitOps 工作流 | 实施 GitOps 实践，使用 Git 作为基础设施和应用的唯一事实来源。 |
| `github-actions-templates` | GitHub Actions 模板 | 创建可复用的 GitHub Actions 工作流模板用于 CI/CD 自动化。 |
| `github-workflow-automation` | GitHub 工作流自动化 | 设计和实现 GitHub Actions 自动化工作流，用于构建、测试和部署。 |
| `gitlab-ci-patterns` | GitLab CI 模式 | 实施 GitLab CI/CD 最佳实践和流水线设计模式。 |
| `circleci-automation` | CircleCI 自动化 | 配置 CircleCI 流水线实现持续集成和部署自动化。 |
| `cicd-automation-workflow-automate` | CI/CD 自动化 | 设计和实施端到端的 CI/CD 自动化工作流。 |
| `grafana-dashboards` | Grafana 仪表板 | 创建和配置 Grafana 监控仪表板，实现数据可视化。 |
| `prometheus-configuration` | Prometheus 配置 | 配置 Prometheus 监控系统，包括抓取规则、告警和记录规则。 |
| `slo-implementation` | SLO 实施 | 定义和实施服务等级目标 (SLO) 和服务等级指标 (SLI)。 |
| `observability-engineer` | 可观测性工程师 | 构建全面的可观测性体系，整合日志、指标和追踪数据。 |
| `observability-monitoring-monitor-setup` | 可观测性监控设置 | 建立完整的监控体系，包括指标收集、告警和可视化。 |
| `observability-monitoring-slo-implement` | 可观测性 SLO 实施 | 基于可观测性数据实施和跟踪服务等级目标。 |
| `service-mesh-expert` | 服务网格专家 | 设计和服务化服务网格架构，包括流量管理、安全和可观测性。 |
| `service-mesh-observability` | 服务网格可观测性 | 在服务网格中实施细粒度的服务间通信监控和追踪。 |
| `istio-traffic-management` | Istio 流量管理 | 配置 Istio 服务网格的流量路由、金丝雀发布和故障注入。 |
| `linkerd-patterns` | Linkerd 模式 | 实施 Linkerd 服务网格的最佳实践和架构模式。 |
| `distributed-tracing` | 分布式追踪 | 实施分布式追踪系统 (如 Jaeger、Zipkin) 进行微服务调用链分析。 |
| `hybrid-cloud-architect` | 混合云架构师 | 设计混合云架构，整合本地数据中心和多个云服务提供商。 |
| `hybrid-cloud-networking` | 混合云网络 | 配置混合云网络连接，包括 VPN、专线和网络安全策略。 |
| `multi-cloud-architecture` | 多云架构 | 设计和实施多云战略，实现跨云提供商的高可用性和容灾。 |

### 安全 (Security)
应用安全、渗透测试、漏洞分析、合规

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `api-security-best-practices` | API 安全最佳实践 | 提供 API 设计和实现中的安全最佳实践指南，包括认证、授权、输入验证和速率限制等。 |
| `api-security-testing` | API 安全测试 | 对 API 端点进行安全测试，识别认证绕过、注入漏洞和不当访问控制等问题。 |
| `sql-injection-testing` | SQL 注入测试 | 检测和验证 SQL 注入漏洞，包括联合查询、盲注和错误注入等攻击类型。 |
| `xss-html-injection` | XSS 与 HTML 注入 | 识别跨站脚本 (XSS) 和 HTML 注入漏洞，包括反射型、存储型和 DOM 型 XSS。 |
| `html-injection-testing` | HTML 注入测试 | 测试应用程序对用户输入的 HTML 标签过滤是否充分，防止内容注入攻击。 |
| `file-path-traversal` | 文件路径遍历 | 检测目录遍历漏洞，防止攻击者通过 ../ 等路径访问敏感文件系统。 |
| `idor-testing` | IDOR 测试 | 测试不安全直接对象引用 (IDOR) 漏洞，验证对象访问控制是否充分。 |
| `broken-authentication` | 认证漏洞测试 | 识别认证机制中的漏洞，包括会话管理、密码策略和多因素认证问题。 |
| `privilege-escalation-methods` | 权限提升方法 | 分析和测试权限提升攻击向量，包括垂直和水平权限提升。 |
| `active-directory-attacks` | Active Directory 攻击 | 模拟针对 Active Directory 的攻击，包括 Kerberoasting、DCSync 和黄金票据等。 |
| `linux-privilege-escalation` | Linux 权限提升 | 识别 Linux 系统中可能的权限提升路径，包括 SUID、内核漏洞和配置错误。 |
| `windows-privilege-escalation` | Windows 权限提升 | 检测 Windows 系统中的权限提升漏洞，包括服务配置、注册表和令牌操作。 |
| `network-101` | 网络基础 | 网络安全基础知识，涵盖 OSI 模型、协议分析和网络架构安全。 |
| `network-engineer` | 网络工程师 | 网络工程和安全配置技能，包括防火墙、路由器和交换机的安全设置。 |
| `pentest-checklist` | 渗透测试清单 | 全面的渗透测试检查清单，确保测试覆盖所有关键安全领域。 |
| `pentest-commands` | 渗透测试命令 | 常用渗透测试命令参考，包括侦察、扫描、利用和后渗透命令。 |
| `vulnerability-scanner` | 漏洞扫描器 | 自动化漏洞扫描技能，使用工具识别系统和应用程序中的安全漏洞。 |
| `red-team-tools` | 红队工具 | 红队行动常用工具集，包括 C2 框架、横向移动和持久化工具。 |
| `red-team-tactics` | 红队战术 | 基于 MITRE ATT&CK 框架的红队战术和技术，模拟真实攻击者行为。 |
| `ethical-hacking-methodology` | 道德黑客方法论 | 系统化的道德黑客测试方法，遵循行业标准渗透测试流程。 |
| `metasploit-framework` | Metasploit 框架 | 使用 Metasploit 框架进行漏洞利用、payload 生成和后渗透测试。 |
| `burp-suite-testing` | Burp Suite 测试 | 使用 Burp Suite 进行 Web 应用程序安全测试，包括代理、扫描器和入侵者模块。 |
| `ffuf-claude-skill` | ffuf 模糊测试 | 使用 ffuf 进行快速 Web 模糊测试，发现隐藏目录、参数和漏洞。 |
| `sqlmap-database-pentesting` | sqlmap 数据库渗透测试 | 使用 sqlmap 自动化 SQL 注入检测和数据库渗透测试。 |
| `ssh-penetration-testing` | SSH 渗透测试 | 测试 SSH 服务配置安全性，包括暴力破解、密钥管理和协议漏洞。 |
| `smtp-penetration-testing` | SMTP 渗透测试 | 测试邮件服务器安全性，识别开放中继、用户枚举和配置问题。 |
| `aws-penetration-testing` | AWS 渗透测试 | 针对 AWS 云环境的渗透测试，包括 IAM、S3、EC2 和 Lambda 安全。 |
| `cloud-penetration-testing` | 云渗透测试 | 多云环境渗透测试方法，覆盖 AWS、Azure、GCP 的安全配置测试。 |
| `wordpress-penetration-testing` | WordPress 渗透测试 | 针对 WordPress 站点的安全测试，包括插件、主题和核心漏洞检测。 |
| `web-security-testing` | Web 安全测试 | 全面的 Web 应用程序安全测试方法，覆盖 OWASP Top 10 漏洞。 |
| `top-web-vulnerabilities` | Top Web 漏洞 | 识别和利用最常见 Web 漏洞的技能，基于 OWASP Top 10 标准。 |
| `security-audit` | 安全审计 | 执行全面的安全审计，评估系统、应用程序和流程的安全状况。 |
| `security-auditor` | 安全审计师 | 专业安全审计技能，包括合规检查、风险评估和报告编写。 |
| `security-scanning-security-sast` | SAST 安全扫描 | 静态应用程序安全测试 (SAST)，在代码层面识别安全漏洞。 |
| `security-scanning-security-dependencies` | 依赖安全扫描 | 扫描项目依赖中的已知漏洞，使用 SCA 工具进行软件成分分析。 |
| `security-scanning-security-hardening` | 安全加固扫描 | 识别系统和应用程序的安全加固机会，减少攻击面。 |
| `sast-configuration` | SAST 配置 | 配置和优化 SAST 工具，减少误报并提高漏洞检测准确性。 |
| `security-compliance-compliance-check` | 安全合规检查 | 执行安全合规性检查，确保符合行业标准和法规要求。 |
| `pci-compliance` | PCI 合规 | PCI DSS 合规实施技能，确保支付卡数据安全处理。 |
| `gdpr-data-handling` | GDPR 数据处理 | GDPR 合规数据处理实践，包括个人数据保护和隐私权实现。 |
| `security-requirement-extraction` | 安全需求提取 | 从业务需求中提取安全要求，确保安全考虑融入设计阶段。 |
| `threat-modeling-expert` | 威胁建模专家 | 系统化威胁建模技能，使用 STRIDE 等方法识别潜在威胁。 |
| `threat-mitigation-mapping` | 威胁缓解映射 | 将识别的威胁映射到具体缓解措施，建立防御策略。 |
| `attack-tree-construction` | 攻击树构建 | 构建攻击树以可视化攻击路径，帮助理解威胁场景和防御优先级。 |
| `reverse-engineer` | 逆向工程 | 软件和硬件逆向工程技能，分析二进制代码和专有协议。 |
| `protocol-reverse-engineering` | 协议逆向工程 | 分析未知网络协议，还原通信格式和加密机制。 |
| `binary-analysis-patterns` | 二进制分析模式 | 二进制文件分析技术和模式识别，用于恶意软件分析和漏洞研究。 |
| `memory-forensics` | 内存取证 | 内存取证分析技能，从内存转储中提取证据和恶意软件痕迹。 |
| `firmware-analyst` | 固件分析师 | 嵌入式设备固件分析，识别后门、硬编码凭证和已知漏洞。 |
| `malware-analyst` | 恶意软件分析师 | 恶意软件静态和动态分析，理解行为特征和感染机制。 |
| `blockchain-developer` | 区块链开发者 | 区块链应用开发技能，包括智能合约、DApp 和共识机制。 |
| `solidity-security` | Solidity 安全 | Solidity 智能合约安全编码实践，防止重入、溢出等常见漏洞。 |
| `nft-standards` | NFT 标准 | NFT 代币标准和安全考虑，包括 ERC-721、ERC-1155 等。 |
| `crypto-bd-agent` | 加密后端代理 | 加密技术在后端的应用，包括密钥管理、加密算法和安全通信。 |
| `mtls-configuration` | mTLS 配置 | 双向 TLS 认证配置，实现服务间安全通信和身份验证。 |
| `secrets-management` | 密钥管理 | 敏感信息管理最佳实践，包括 API 密钥、密码和证书的存储与轮换。 |
| `frontend-security-coder` | 前端安全开发 | 前端安全编码实践，防止 XSS、CSRF 和客户端数据泄露。 |
| `backend-security-coder` | 后端安全开发 | 后端安全编码实践，包括输入验证、SQL 注入防护和访问控制。 |
| `mobile-security-coder` | 移动安全开发 | 移动应用安全开发技能，覆盖 iOS 和 Android 平台的安全最佳实践。 |
| `k8s-security-policies` | K8s 安全策略 | Kubernetes 安全策略配置，包括 Pod 安全标准、网络策略和 RBAC。 |
| `security-bluebook-builder` | 安全蓝皮书构建 | 构建组织安全文档和策略手册，建立安全基线和操作指南。 |
| `cc-skill-security-review` | Claude Code 安全审查 | 针对 Claude Code 会话和项目代码的安全审查技能。 |
| `web3-testing` | Web3 测试 | 去中心化应用 (DApp) 安全测试，包括智能合约和区块链交互测试。 |
| `defi-protocol-templates` | DeFi 协议模板 | DeFi 协议安全开发和审计模板，覆盖借贷、交易和挖矿池模式。 |
| `wireshark-analysis` | Wireshark 分析 | 使用 Wireshark 进行网络流量分析，识别异常通信和安全事件。 |
| `shodan-reconnaissance` | Shodan 侦察 | 使用 Shodan 搜索引擎进行信息收集，发现暴露的设备和漏洞。 |
| `anti-reversing-techniques` | 反逆向技术 | 软件保护技术，防止逆向工程和代码分析，包括混淆和加壳。 |
| `memory-safety-patterns` | 内存安全模式 | 内存安全编程模式，防止缓冲区溢出、释放后使用和堆栈破坏。 |
| `varlock-claude-skill` | Varlock 变量锁定 | 变量安全锁定技能，防止敏感变量被未授权访问或修改。 |

### 测试 (Testing)
TDD、测试设计、修复、QA 工作流

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `test-driven-development` | 测试驱动开发 | 采用 TDD 方法论，先写测试再实现功能的开发方式。 |
| `tdd-workflow` | TDD 工作流 | 实现测试驱动的标准化开发流程。 |
| `tdd-orchestrator` | TDD 编排器 | 协调和管理 TDD 开发流程的各个环节。 |
| `tdd-workflows-tdd-red` | TDD 工作流 - 红阶段 | TDD 循环中编写失败测试的红色阶段。 |
| `tdd-workflows-tdd-cycle` | TDD 工作流 - 完整循环 | 完整的 TDD 红 - 绿 - 重构循环流程。 |
| `tdd-workflows-tdd-green` | TDD 工作流 - 绿阶段 | TDD 循环中实现功能使测试通过的绿色阶段。 |
| `tdd-workflows-tdd-refactor` | TDD 工作流 - 重构阶段 | TDD 循环中优化代码结构的重构阶段。 |
| `testing-patterns` | 测试模式 | 软件测试的最佳实践和常见设计模式。 |
| `testing-qa` | 测试与 QA | 质量保证和测试流程的综合方法。 |
| `e2e-testing` | 端到端测试 | 从用户角度验证完整应用流程的测试方法。 |
| `e2e-testing-patterns` | 端到端测试模式 | 实现端到端测试的最佳实践和模式。 |
| `webapp-testing` | Web 应用测试 | 针对 Web 应用程序的功能和集成测试。 |
| `playwright-skill` | Playwright 测试 | 使用 Playwright 进行浏览器自动化和端到端测试。 |
| `go-playwright` | Go Playwright | 使用 Go 语言的 Playwright 进行 Web 自动化测试。 |
| `go-rod-master` | Go-Rod 专家 | 使用 Go-Rod 库进行浏览器自动化控制。 |
| `javascript-testing-patterns` | JavaScript 测试模式 | JavaScript 代码的测试策略和最佳实践。 |
| `python-testing-patterns` | Python 测试模式 | Python 代码的测试框架和最佳实践。 |
| `bats-testing-patterns` | BATS 测试模式 | Bash 自动化测试脚本（BATS）的测试模式。 |
| `unit-testing-test-generate` | 单元测试生成 | 自动生成单元测试用例以覆盖代码逻辑。 |
| `test-automator` | 测试自动化师 | 自动化测试用例的创建和执行流程。 |
| `test-fixing` | 测试修复 | 诊断和修复失败的测试用例。 |
| `fix-review` | 修复审查 | 审查和验证代码修复的正确性和完整性。 |
| `qa-test-planner` | QA 测试规划师 | 制定全面的测试计划和覆盖策略。 |
| `performance-testing-review-ai-review` | 性能测试 - AI 审查 | 使用 AI 辅助审查性能测试结果和建议。 |
| `performance-testing-review-multi-agent-review` | 性能测试 - 多代理审查 | 多代理协作审查系统性能和瓶颈。 |
| `performance-profiling` | 性能分析 | 分析和优化代码性能瓶颈。 |
| `llm-evaluation` | LLM 评估 | 评估 LLM 模型的准确性、安全性和性能。 |
| `evaluation` | 评估专家 | 系统化的软件质量和性能评估方法。 |
| `agent-evaluation` | 代理评估 | 评估 AI 代理的行为和输出质量。 |
| `screen-reader-testing` | 屏幕阅读器测试 | 测试应用与屏幕阅读器的兼容性以确保无障碍访问。 |
| `accessibility-compliance-accessibility-audit` | 无障碍合规审计 | 审查应用的无障碍功能和合规性。 |
| `wcag-audit-patterns` | WCAG 审计模式 | 按照 WCAG 标准进行无障碍审计的模式。 |
| `laravel-security-audit` | Laravel 安全审计 | 审查 Laravel 应用的安全漏洞和最佳实践。 |

### 工作流 (Workflow)
自动化、编排、任务、代理

| 技能 | 中文名称 | 描述 |
|------|------|------|
| `workflow-automation` | 工作流自动化 | 自动化重复任务和业务流程，提高效率和一致性。 |
| `workflow-patterns` | 工作流模式 | 识别和应用常见的工作流模式以优化流程设计。 |
| `workflow-orchestration-patterns` | 工作流编排模式 | 设计和实现复杂工作流的编排策略，协调多个步骤和服务。 |
| `inngest` | Inngest 专家 | 使用 Inngest 构建事件驱动的工作流和定时任务。 |
| `trigger-dev` | Trigger.dev 专家 | 使用 Trigger.dev 平台开发和调度后台任务。 |
| `bullmq-specialist` | BullMQ 专家 | 使用 BullMQ 实现 Redis 队列和任务处理系统。 |
| `temporal-python-pro` | Temporal Python 专家 | 使用 Temporal 在 Python 中构建可靠的工作流和微服务编排。 |
| `temporal-golang-pro` | Temporal Go 专家 | 使用 Temporal 在 Go 中构建可靠的工作流和微服务编排。 |
| `temporal-python-testing` | Temporal Python 测试 | 测试和验证 Temporal Python 工作流的正确性和可靠性。 |
| `saga-orchestration` | Saga 编排 | 实现 Saga 模式以管理分布式事务和回滚逻辑。 |
| `event-sourcing-architect` | 事件溯源架构师 | 设计基于事件溯源的系统架构，记录所有状态变更。 |
| `event-store-design` | 事件存储设计 | 设计和实现高效的事件存储系统以支持事件溯源。 |
| `cqrs-implementation` | CQRS 实现 | 实现命令查询职责分离架构以优化读写性能。 |
| `projections` | 投影 | 从事件流构建读模型投影以支持高效查询。 |
| `projection-patterns` | 投影模式 | 应用事件溯源中的投影模式以优化数据视图。 |
| `parallel-agents` | 并行代理 | 协调多个 AI 代理并行执行任务以提高效率。 |
| `dispatching-parallel-agents` | 并行代理调度 | 调度和分配任务给多个并行运行的 AI 代理。 |
| `multi-agent-brainstorming` | 多代理头脑风暴 | 利用多个 AI 代理进行创意发散和问题解决。 |
| `subagent-driven-development` | 子代理驱动开发 | 使用专门化的子代理处理特定开发任务。 |
| `agent-manager-skill` | 代理管理器 | 管理和协调多个 AI 代理的执行和通信。 |
| `context-driven-development` | 上下文驱动开发 | 基于上下文信息进行智能化的开发决策。 |
| `context-management-context-save` | 上下文保存 | 保存当前会话上下文以便后续恢复和继续使用。 |
| `context-management-context-restore` | 上下文恢复 | 从已保存的状态恢复会话上下文。 |
| `context-compression` | 上下文压缩 | 压缩和简化上下文信息以优化 token 使用。 |
| `context-window-management` | 上下文窗口管理 | 有效管理有限的上下文窗口以处理长对话。 |
| `context-fundamentals` | 上下文基础 | 理解和管理 AI 会话上下文的核心概念。 |
| `context-manager` | 上下文管理器 | 统一管理会话上下文的存储和检索。 |
| `context7-auto-research` | 自动研究 | 自动执行研究任务并收集相关上下文信息。 |
| `memory-systems` | 记忆系统 | 设计和实现 AI 代理的记忆存储和检索机制。 |
| `conversation-memory` | 对话记忆 | 跟踪和存储对话历史以保持连贯性。 |
| `agent-memory-mcp` | 代理记忆 MCP | 使用 MCP 协议实现代理间共享记忆。 |
| `hierarchical-agent-memory` | 层级代理记忆 | 实现分层记忆结构以组织和管理代理知识。 |
| `computer-use-agents` | 计算机使用代理 | 使 AI 代理能够操作计算机界面和执行 GUI 任务。 |
| `autonomous-agents` | 自主代理 | 构建能够自主规划和执行复杂任务的 AI 代理。 |
| `ai-wrapper-product` | AI 包装产品 | 将 AI 能力封装为独立产品或服务的策略。 |
| `ai-product` | AI 产品 | 设计和开发以 AI 为核心功能的产品。 |
| `free-tool-strategy` | 免费工具策略 | 通过免费工具吸引用户并实现转化的策略。 |
| `micro-saas-launcher` | 微型 SaaS 启动器 | 快速启动和发布微型 SaaS 产品的完整流程。 |
| `launch-strategy` | 发布策略 | 规划和执行产品发布以获得最大市场影响力。 |
| `viral-generator-builder` | 病毒传播生成器 | 创建具有病毒式传播潜力的内容生成工具。 |
| `growth-hacking` | 增长黑客 | 运用数据驱动的实验策略实现快速增长。 |
| `product-manager-toolkit` | 产品经理工具箱 | 产品经理所需的全套工具和方法论。 |

---

## Yeachan-Heo/oh-my-claudecode

**仓库**: https://github.com/Yeachan-Heo/oh-my-claudecode

**安装**:
```bash
/plugin marketplace add https://github.com/Yeachan-Heo/oh-my-claudecode
/plugin install oh-my-claudecode
/omc-setup

# parcadei/continuous-claude-v3
git clone https://github.com/parcadei/Continuous-Claude-v3.git
cd Continuous-Claude-v3/opc
uv run python -m scripts.setup.wizard
```

### 斜杠命令 (35+)

| 命令 | 描述 |
|------|------|
| `/analyze` | 深度代码分析 |
| `/autopilot` | 自动执行模式 |
| `/build-fix` | 构建和修复错误 |
| `/cancel` | 取消正在运行的任务 |
| `/ccg` | 三模型 Codex+Gemini 编排 |
| `/code-review` | 全面的代码审查 |
| `/configure-notifications` | 配置通知设置 |
| `/configure-openclaw` | 配置 OpenCLaw 集成 |
| `/deep-interview` | 苏格拉底式需求澄清 |
| `/deepinit` | 深度初始化 |
| `/external-context` | 加载外部上下文 |
| `/hud` | 显示 HUD 状态 |
| `/learn-about-omc` | 了解 OMC |
| `/learner` | 学习模式 |
| `/mcp-setup` | 设置 MCP |
| `/note` | 添加笔记 |
| `/omc-doctor` | 诊断工具 |
| `/omc-help` | 获取帮助 |
| `/omc-setup` | 设置 OMC |
| `/omc-teams` | 生成 tmux CLI 工作器 |
| `/plan` | 规划访谈 |
| `/project-session-manager` | 管理项目会话 |
| `/ralph` | 带有验证/修复循环的持久模式 |
| `/ralph-init` | 初始化 Ralph |
| `/ralplan` | 迭代规划共识 |
| `/release` | 发布管理 |
| `/sciomc` | 科学模式 |
| `/security-review` | 安全审查 |
| `/skill` | 技能管理 |
| `/tdd` | TDD 模式 |
| `/team` | 团队编排 |
| `/trace` | 追踪执行 |
| `/ultraqa` | 超级 QA 模式 |
| `/ultrawork` | 最大并行度 |
| `/writer-memory` | 写手内存管理 |

### 专业代理 (21)

| 代理 | 描述 |
|------|------|
| `analyst` | 商业和技术分析 |
| `architect` | 系统架构设计 |
| `build-fixer` | 修复构建错误 |
| `code-reviewer` | 代码审查专家 |
| `code-simplifier` | 简化复杂代码 |
| `critic` | 关键分析和反馈 |
| `debugger` | 调试复杂问题 |
| `deep-executor` | 深度任务执行 |
| `designer` | UI/UX 设计 |
| `document-specialist` | 文档专家 |
| `executor` | 任务执行 |
| `explore` | 代码库探索 |
| `git-master` | Git 操作专家 |
| `planner` | 规划和策略 |
| `qa-tester` | 质量保证测试 |
| `quality-reviewer` | 质量审查 |
| `scientist` | 研究和分析 |
| `security-reviewer` | 安全分析 |
| `test-engineer` | 测试工程 |
| `verifier` | 验证和确认 |
| `writer` | 技术写作 |

### 编排模式

| 模式 | 描述 | 适用场景 |
|------|------|----------|
| **Team** | 经典的分阶段流水线 | 协调 Claude 代理 |
| **omc-teams** | tmux CLI 工作器 | Codex/Gemini CLI 任务 |
| **ccg** | 三模型编排 | 混合后端 +UI 工作 |
| **Autopilot** | 自动执行 | 端到端功能 |
| **Ultrawork** | 最大并行度 | 突发并行修复 |
| **Ralph** | 持久模式 | 需要完成的任务 |
| **Pipeline** | 顺序处理 | 多步骤转换 |

---

## 快速参考

### 安装摘要

```bash
# softaworks/agent-toolkit
npx skills add softaworks/agent-toolkit

# sickn33/antigravity-awesome-skills
npx skills add sickn33/antigravity-awesome-skills

# Yeachan-Heo/oh-my-claudecode
/plugin marketplace add https://github.com/Yeachan-Heo/oh-my-claudecode
/plugin install oh-my-claudecode
/omc-setup

# parcadei/continuous-claude-v3
git clone https://github.com/parcadei/Continuous-Claude-v3.git
cd Continuous-Claude-v3/opc
uv run python -m scripts.setup.wizard
```

### 技能数量摘要

| 仓库 | 技能 | 代理 | 命令 |
|------|------|------|------|
| softaworks/agent-toolkit | 50+ | 6 | 7 |
| sickn33/antigravity-awesome-skills | 960+ | - | - |
| Yeachan-Heo/oh-my-claudecode | - | 21 | 35+ |
| parcadei/continuous-claude-v3 | 109+ | 32 | 30 |

### 热门分类 (Antigravity)

1. **开发 (Development)** - 100+ 适用于所有主要语言和框架的技能
2. **安全 (Security)** - 60+ 应用安全、渗透测试和合规技能
3. **数据与 AI (Data & AI)** - 50+ LLM 应用、RAG 和 ML 技能
4. **基础设施 (Infrastructure)** - 80+ 云、DevOps 和部署技能
5. **商业 (Business)** - 20+ SEO、营销和战略技能
6. **测试 (Testing)** - 30+ TDD、E2E 和 QA 技能
7. **工作流 (Workflow)** - 30+ 自动化和编排技能

---

## vibeforge1111/vibeship-spawner-skills

**仓库**: https://github.com/vibeforge1111/vibeship-spawner-skills

**技能总数**: 462+

**安装**:
```bash
# 完整安装（包含 MCP 服务器）
npx github:vibeforge1111/vibeship-spawner-skills install --mcp

# 仅安装技能
npx github:vibeforge1111/vibeship-spawner-skills install

# 更新技能
npx github:vibeforge1111/vibeship-spawner-skills update
```

### 四文件技能系统

Spawner Skills 使用独特的 4 文件结构，每个技能包含：

```
maker/micro-saas-launcher/
├── skill.yaml          # 身份、模式、反模式、交接
├── sharp-edges.yaml    # 陷阱和警告
├── validations.yaml    # 自动化代码质量检查
└── collaboration.yaml  # 技能协作配置
```

| 特性 | 普通提示词 | Spawner Skills |
|------|-----------|---------------|
| **模式** | 通用建议 | 经过验证的实现代码 |
| **反模式** | 无 | "不要这样做因为..." + 替代方案 |
| **陷阱警告** | 无 | 自动检测的陷阱 |
| **验证** | 无 | 正则表达式检查错误 |
| **协作** | 无 | 技能互相委托 |
| **严重程度** | 无 | 关键、高、中、低 |

### 技能类别 (35 categories)

| 类别 | 技能数 | 描述 |
|------|--------|------|
| **AI & ML** | 59 | LLM 架构、RAG、微调、多模态 AI |
| **AI Agents** | 23 | 自主代理、多代理编排、MCP |
| **AI Tools** | 12 | 代码生成、图像/视频/音频处理 |
| **Game Dev** | 51 | Unity、Godot、游戏设计、3D 建模 |
| **Marketing** | 36 | 内容策略、SEO、病毒式营销 |
| **Integrations** | 25 | Stripe、AWS、Discord、Slack 等 |
| **Strategy** | 24 | 产品战略、融资、市场竞争 |
| **DevOps** | 22 | K8s、Docker、CI/CD、监控 |
| **Backend** | 21 | API、微服务、缓存、实时通信 |
| **Blockchain** | 20 | 智能合约、DeFi、NFT、Solana |
| **Security** | 13 | OAuth、加密、渗透测试 |
| **Design** | 12 | UI/UX、品牌、无障碍设计 |
| **Frameworks** | 12 | Next.js、React、Svelte、Tailwind |
| **Community** | 11 | Discord、Telegram、开发者社区 |
| **Data** | 11 | PostgreSQL、Redis、向量数据库 |
| **Maker** | 11 | 病毒生成器、Telegram Bot、扩展 |
| **Mind** | 10 | 调试、决策、系统设计 |
| **Development** | 9 | 文档、性能、CLI、SDK |
| **Frontend** | 8 | 状态管理、表单、PWA |
| **Testing** | 8 | 测试架构、E2E、性能测试 |
| **Education** | 7 | 课程创建、直播教学 |
| **Product** | 7 | A/B 测试、分析、用户研究 |
| **Biotech** | 6 | 基因组学、药物发现 |
| **Enterprise** | 6 | 合规、数据治理 |
| **Finance** | 6 | 算法交易、投资组合 |
| **Hardware** | 6 | 嵌入式、ROS2、FPGA |
| **Trading** | 6 | 执行算法、量化研究 |
| **Climate** | 5 | 碳足迹、能源优化 |
| **Communications** | 5 | 技术演讲、投资者沟通 |
| **Legal** | 5 | GDPR、合同、专利 |
| **Simulation** | 5 | 蒙特卡洛、数字孪生 |
| **Space** | 5 | 轨道力学、任务规划 |
| **Science** | 4 | 实验设计、统计学 |
| **Startup** | 3 | YC 最佳实践、创始人模式 |
| **Creative** | 23 | 梗图、游戏化、病毒钩子 |

### 使用技能

#### 在 Claude 中加载技能
```bash
# 让 Claude 读取技能文件
Read: ~/.spawner/skills/maker/micro-saas-launcher/skill.yaml
```

#### 使用 MCP 工具
```bash
# 搜索技能
spawner_skills({ query: "telegram bot" })

# 加载特定技能
spawner_load({ skill_id: "telegram-bot-builder" })
```

#### 在线浏览
访问 **[spawner.vibeship.co/skills](https://spawner.vibeship.co/skills)** 查看交互式目录。

完整技能列表请查看：[VIBESHIP-SKILLS.md](VIBESHIP-SKILLS.md)

---

## parcadei/continuous-claude-v3

**仓库**: https://github.com/parcadei/Continuous-Claude-v3

**技能总数**: 109+ | **代理**: 32 | **钩子**: 30

**安装**:
```bash
# 克隆项目
git clone https://github.com/parcadei/Continuous-Claude-v3.git
cd Continuous-Claude-v3/opc

# 运行设置向导（12 步）
uv run python -m scripts.setup.wizard
```

> **注意**: `pyproject.toml` 在 `opc/` 目录中。始终从 `opc/` 目录运行 `uv` 命令。

### 核心理念

**Continuous Claude** 将 Claude Code 转变为一个持续学习的系统，在会话间维护上下文，编排专业代理，并通过智能代码分析消除 token 浪费。

| 问题 | 解决方案 |
|------|----------|
| 上下文压缩时丢失信息 | YAML 交接 - 更高效的 token 传输 |
| 每次会话从头开始 | 记忆系统召回 + 守护进程自动提取学习内容 |
| 读取整个文件消耗 token | 5 层代码分析 + 语义索引 |
| 复杂任务需要协调 | 元技能编排代理工作流 |
| 手动重复工作流 | 109 个技能，自然语言触发 |

**座右铭：复合，不要压缩。** 自动提取学习内容，然后以完整上下文重新开始。

---

### 元技能（工作流编排器）

| 元技能 | 链式流程 | 使用时机 |
|--------|----------|----------|
| `/workflow` | 路由 → 适当的工作流 | 不知道从哪里开始 |
| `/build` | discovery → plan → validate → implement → commit | 构建功能 |
| `/fix` | sleuth → premortem → kraken → test → commit | 修复 bug |
| `/tdd` | plan → arbiter (tests) → kraken (implement) → arbiter | 测试优先开发 |
| `/refactor` | phoenix → plan → kraken → reviewer → arbiter | 安全代码转换 |
| `/review` | 并行专业审查 → 综合 | 代码审查 |
| `/explore` | scout (quick/deep/architecture) | 理解代码库 |
| `/security` | 漏洞扫描 → 验证 | 安全审计 |
| `/release` | audit → E2E → review → changelog | 发布版本 |

---

### 核心技能

#### 会话管理

| 技能 | 描述 |
|------|------|
| `create_handoff` | 创建 YAML 格式的会话交接文档，保存状态和上下文 |
| `resume_handoff` | 恢复之前的会话交接，加载保存的状态 |
| `continuity_ledger` | 维护连续性分类账，跟踪会话状态 |
| `complete-skill` | 标记任务完成并触发学习提取 |
| `completion-check` | 检查任务完成状态 |

#### 代码分析

| 技能 | 描述 |
|------|------|
| `tldr-code` | 使用 TLDR 5 层分析压缩代码表示（节省 95% token） |
| `tldr-deep` | 深度 TLDR 分析，包含更多上下文 |
| `tldr-overview` | 代码库概览 TLDR |
| `tldr-router` | 智能路由到适当的 TLDR 技能 |
| `tldr-stats` | 代码统计和指标 |
| `ast-grep-find` | 使用 ast-grep 进行 AST 级别代码搜索 |
| `dead-code` | 检测和分析死代码 |

#### 开发与调试

| 技能 | 描述 |
|------|------|
| `build` | 构建工作流技能 |
| `fix` | 调试和修复工作流 |
| `debug` | 通用调试技能 |
| `debug-hooks` | 调试钩子问题 |
| `commit` | 高质量的 git 提交 |
| `git-commits` | git 提交管理 |
| `describe_pr` | 生成 PR 描述 |
| `implement_plan` | 实现计划 |
| `implement_plan_micro` | 微任务实现 |
| `implement_task` | 任务实现 |

#### 规划与设计

| 技能 | 描述 |
|------|------|
| `plan-agent` | 创建详细的实现计划 |
| `premortem` | 实施前风险分析 |
| `discovery-interview` | 需求澄清访谈 |
| `explore` | 代码库探索 |

#### 重构与质量

| 技能 | 描述 |
|------|------|
| `refactor` | 代码重构工作流 |
| `review` | 代码审查 |
| `qlty-check` | 质量检查 |
| `qlty-during-development` | 开发过程中的质量保证 |
| `validate-agent` | 验证代理输出 |

#### 研究与学习

| 技能 | 描述 |
|------|------|
| `research` | 代码库研究 |
| `research-agent` | 研究代理 |
| `research-external` | 外部研究 |
| `recall` | 记忆召回 |
| `recall-reasoning` | 基于记忆的推理 |
| `remember` | 保存学习内容 |
| `compound-learnings` | 复合学习内容 |

#### 数学技能

| 技能 | 描述 |
|------|------|
| `math-help` | 数学帮助 |
| `math-router` | 数学路由 |
| `math-unified` | 统一数学技能 |
| `prove` | 证明辅助 |
| `pint-compute` | 单位计算 |
| `shapely-compute` | 几何计算 |

**数学子技能**:
- 实分析：极限、连续性、收敛性
- 复分析：解析函数、轮廓积分、留数
- 线性代数：向量空间、矩阵、特征值
- 抽象代数：群、环、域
- 拓扑：开集、紧致性、连通性
- 测度论：σ-代数、Lebesgue 测度、积分论
- 数理逻辑：命题逻辑、谓词逻辑、证明论
- 常微分方程和偏微分方程
- 数值方法：插值、数值积分、求根
- 优化：梯度方法、约束优化、凸优化
- 泛函分析：Banach 空间、Hilbert 空间、算子理论
- 信息论：熵、信道容量、信源编码
- 图论与数论
- 范畴论：范畴与函子、自然变换、极限与余极限

#### Agent 相关

| 技能 | 描述 |
|------|------|
| `agent-orchestration` | 代理编排 |
| `agentic-workflow` | 代理工作流 |
| `agent-context-isolation` | 代理上下文隔离 |
| `parallel-agents` | 并行代理 |
| `parallel-agent-contracts` | 并行代理契约 |
| `sub-agents` | 子代理管理 |
| `background-agent-pings` | 后台代理心跳 |
| `no-polling-agents` | 无轮询代理模式 |

#### Agentica（多代理框架）

| 技能 | 描述 |
|------|------|
| `agentica-claude-proxy` | Agentica Claude 代理 |
| `agentica-infrastructure` | Agentica 基础设施 |
| `agentica-prompts` | Agentica 提示词 |
| `agentica-sdk` | Agentica SDK |
| `agentica-server` | Agentica 服务器 |
| `agentica-spawn` | Agentica 生成 |

#### 搜索与信息检索

| 技能 | 描述 |
|------|------|
| `search-hierarchy` | 搜索层级 |
| `search-router` | 搜索路由 |
| `search-tools` | 搜索工具 |
| `loogle-search` | Loogle 搜索 |
| `firecrawl-scrape` | Firecrawl 爬取 |
| `perplexity-search` | Perplexity 搜索 |
| `github-search` | GitHub 搜索 |

#### 钩子与系统

| 技能 | 描述 |
|------|------|
| `hooks` | 钩子系统 |
| `hook-developer` | 钩子开发 |
| `session_start-recall` | 会话开始时召回记忆 |
| `working_on` | 工作状态跟踪 |

#### 代码质量与规范

| 技能 | 描述 |
|------|------|
| `modular-code` | 模块化代码 |
| `observe-before-editing` | 编辑前观察 |
| `index-at-creation` | 创建时索引 |
| `graceful-degradation` | 优雅降级 |
| `idempotent-redundancy` | 幂等冗余 |
| `explicit-identity` | 显式身份 |

#### 文档与帮助

| 技能 | 描述 |
|------|------|
| `help` | 帮助技能 |
| `tour` | 项目导览 |
| `system_overview` | 系统概览 |
| `onboard` | 入职引导 |
| `cli-reference` | CLI 参考 |
| `repoprompt` | 仓库提示生成 |
| `repo-research-analyst` | 仓库研究分析师 |

#### 高级技能

| 技能 | 描述 |
|------|------|
| `mot` | 元操作理论 |
| `wiring` | 系统连接 |
| `migrate` | 迁移技能 |
| `mcp-chaining` | MCP 链接 |
| `mcp-scripts` | MCP 脚本 |
| `morph-apply` | 形态应用 |
| `morph-search` | 形态搜索 |
| `reference-sdk` | 参考 SDK |
| `release` | 发布管理 |
| `tdd` | 测试驱动开发 |
| `tdd-migrate` | TDD 迁移 |
| `tdd-migration-pipeline` | TDD 迁移流水线 |
| `test` | 测试技能 |
| `security` | 安全技能 |
| `workflow-router` | 工作流路由 |
| `slash-commands` | 斜杠命令 |
| `skill-developer` | 技能开发 |
| `skill-development` | 技能发展 |
| `skill-upgrader` | 技能升级 |
| `opc-architecture` | OPC 架构 |

#### Braintrust（追踪与分析）

| 技能 | 描述 |
|------|------|
| `braintrust-tracing` | Braintrust 追踪 |
| `braintrust-analyze` | Braintrust 分析 |

#### 遗留/归档技能

| 技能 | 状态 |
|------|------|
| `router-first-architecture` | 归档 |
| `async-repl-protocol` | 归档 |
| `leann-search` | 归档 |

---

### 代理系统 (32 Agents)

| 代理 | 描述 |
|------|------|
| `aegis` | 安全防护代理 |
| `agentica-agent` | Agentica 专用代理 |
| `arbiter` | 测试验证代理 |
| `architect` | 架构设计代理 |
| `atlas` | 文档和知识代理 |
| `braintrust-analyst` | Braintrust 数据分析 |
| `chronicler` | 记录和文档代理 |
| `context-query-agent` | 上下文查询代理 |
| `critic` | 关键分析和反馈 |
| `debug-agent` | 专业调试代理 |
| `herald` | 通知和通信代理 |
| `judge` | 代码质量评审 |
| `kraken` | 主要执行代理 |
| `liaison` | 联络和协调代理 |
| `maestro` | 编排指挥代理 |
| `memory-extractor` | 记忆提取代理 |
| `onboard` | 入职引导代理 |
| `oracle` | 研究和分析代理 |
| `pathfinder` | 路径查找代理 |
| `phoenix` | 重构和现代化代理 |
| `plan-agent` | 规划代理 |
| `plan-reviewer` | 计划审查代理 |
| `profiler` | 性能分析代理 |
| `research-codebase` | 代码库研究代理 |
| `review-agent` | 代码审查代理 |
| `scout` | 探索和侦察代理 |
| `scribe` | 文档编写代理 |
| `sentinel` | 监控和守护代理 |
| `session-analyst` | 会话数据分析 |
| `sleuth` | 调查和诊断代理 |
| `spark` | 创意和头脑风暴代理 |
| `surveyor` | 测量和评估代理 |
| `validate-agent` | 验证代理 |
| `warden` | 代码质量和规范代理 |

---

### 钩子系统 (30 Hooks)

钩子在特定事件时自动触发，注入上下文和执行验证。

#### 会话生命周期钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `session-start-continuity` | 会话开始 | 加载连续性分类账和交接 |
| `session-start-recall` | 会话开始 | 召回相关记忆 |
| `session-start-tldr-cache` | 会话开始 | 加载 TLDR 缓存 |
| `session-start-dead-code` | 会话开始 | 死代码检测初始化 |
| `session-register` | 会话开始 | 注册会话到数据库 |
| `session-end-cleanup` | 会话结束 | 清理和保存状态 |
| `session-outcome` | 会话结束 | 记录会话结果 |
| `session-symbol-index` | 会话期间 | 符号索引构建 |

#### 编译时钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `pre-compact-continuity` | 压缩前 | 自动交接前上下文压缩 |
| `pre-tool-use` | 工具使用前 | 工具使用验证 |
| `pre-tool-use-broadcast` | 工具使用前 | 广播工具使用事件 |
| `pre-edit-context` | 编辑前 | 注入编辑上下文 |
| `edit-context-inject` | 编辑时 | 编辑上下文注入 |
| `post-tool-use` | 工具使用后 | 工具使用后处理 |
| `post-task-complete` | 任务完成 | 任务完成处理 |
| `post-edit-notify` | 编辑后 | 编辑后通知 |
| `post-edit-diagnostics` | 编辑后 | 编辑后诊断 |

#### 技能和代理钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `skill-activation-prompt` | 用户消息 | 注入技能激活建议 |
| `skill-context-inject` | 技能激活 | 注入技能上下文 |
| `skill-validation-prompt` | 技能使用 | 技能验证 |
| `skill-router` | 用户消息 | 路由到适当技能 |
| `agent-state-broadcast` | 代理事件 | 广播代理状态 |
| `subagent-start` | 子代理启动 | 子代理启动处理 |
| `subagent-stop` | 子代理停止 | 子代理停止处理 |
| `subagent-learning` | 子代理停止 | 从子代理提取学习 |

#### 代码质量钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `compiler-in-the-loop` | 编辑后 | 编译器验证 |
| `compiler-in-the-loop-stop` | 子代理停止 | 编译后验证 |
| `typescript-preflight` | TypeScript 编辑 | TypeScript 预检查 |
| `import-validator` | 编辑后 | 导入验证 |
| `import-error-detector` | 编辑后 | 导入错误检测 |
| `file-claims` | 文件操作 | 文件声明跟踪 |
| `path-rules` | 文件访问 | 路径规则执行 |
| `impact-refactor` | 重构前 | 评估重构影响 |

#### 记忆和学习钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `memory-awareness` | 会话期间 | 记忆系统感知 |
| `auto-handoff-stop` | 会话结束 | 自动创建交接 |
| `handoff-index` | 交接创建 | 交接索引 |
| `user-confirm-learning` | 学习提取 | 用户确认学习内容 |

#### 工作流和模式钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `pattern-orchestrator` | 工作流 | 编排设计模式 |
| `composition-gate` | 工作流 | 组合模式门控 |
| `phase-gate` | 工作流 | 阶段门控 |
| `explorer-to-scout` | 探索 | 探索到侦察转换 |
| `erotetic-clarification` | 需求模糊 | 苏格拉底式澄清 |
| `signature-helper` | 签名检测 | 签名变更检测 |
| `spec-anchor` | 规范编辑 | 规范锚定 |
| `spec-intent-detector` | 规范编辑 | 规范意图检测 |

#### 资源管理钩子

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `resource-gate` | 资源访问 | 资源访问门控 |
| `arch-context-inject` | 架构操作 | 架构上下文注入 |

#### 守护进程和后台任务

| 钩子 | 触发时机 | 描述 |
|------|----------|------|
| `heartbeat` | 定期 | 会话心跳 |
| `drift-detector` | 定期 | 上下文漂移检测 |
| `transcript-parser` | 会话结束 | 转录解析 |
| `tldr-context-inject` | 读取文件 | TLDR 上下文注入 |
| `tldr-rebuild-prompt` | 代码变更 | TLDR 重建 |
| `tldr-read-enforcer` | 读取文件 | 强制使用 TLDR |

---

### TLDR 5 层代码分析

TLDR (Token-Light Document Representation) 是一个 5 层代码分析系统，可将代码表示压缩 95%。

| 层级 | 名称 | Token 数 | 内容 |
|------|------|---------|------|
| L1 | AST | ~500 | 函数、类、签名 |
| L2 | 调用图 | +440 | 跨文件依赖 |
| L3 | 控制流图 | +110 | 控制流 |
| L4 | 数据流图 | +130 | 数据流 |
| L5 | 程序依赖图 | +150 | 切片 |

**总计**: ~1,200 tokens vs 23,000 原始 tokens = **95% 节省**

---

### 记忆系统

使用 PostgreSQL + pgvector 的记忆系统：

| 表 | 描述 |
|-----|------|
| `sessions` | 会话心跳跟踪 |
| `file_claims` | 文件锁和声明 |
| `archival_memory` | 使用 BGE 嵌入的归档记忆 |
| `handoffs` | 嵌入的会话交接 |

---

### 技能激活系统

当用户发送消息时，钩子注入上下文，告诉 Claude 哪些技能和代理是相关的。

```
> "修复登录 bug"

🎯 技能激活检查
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚠️ 关键技能 (必需):
  → create_handoff

📚 推荐技能:
  → fix
  → debug

🤖 推荐代理 (token 高效):
  → debug-agent
  → scout

动作：使用 Skill 工具在响应前
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

#### 优先级级别

| 级别 | 含义 |
|------|------|
| ⚠️ **关键** | 必须使用（如会话结束前的交接） |
| 📚 **推荐** | 应该使用（如工作流技能） |
| 💡 **建议** | 考虑使用（如优化工具） |
| 📌 **可选** | 最好有（如文档助手） |

---

### 工作流链示例

```
/fix bug                              /build greenfield
─────────                             ─────────────────
┌──────────┐  ┌──────────┐            ┌──────────┐  ┌──────────┐
│  sleuth  │─▶│ premortem│            │discovery │─▶│plan-agent│
│(诊断)    │  │  (风险)  │            │(澄清)    │  │ (设计)   │
└──────────┘  └────┬─────┘            └──────────┘  └────┬─────┘
                   │                                      │
                   ▼                                      ▼
            ┌──────────┐                          ┌──────────┐
            │  kraken  │                          │ validate │
            │  (修复)  │                          │ (检查)   │
            └────┬─────┘                          └────┬─────┘
                 │                                      │
                 ▼                                      ▼
            ┌──────────┐                          ┌──────────┐
            │  arbiter │                          │  kraken  │
            │ (测试)   │                          │(实现)    │
            └────┬─────┘                          └────┬─────┘
                 │                                      │
                 ▼                                      ▼
            ┌──────────┐                          ┌──────────┐
            │  commit  │                          │  commit  │
            └──────────┘                          └──────────┘
```

---

### 配置

设置环境变量：

```bash
# 数据库连接
export CONTINUOUS_CLAUDE_DB_URL="postgresql://user:password@localhost:5432/continuous_claude"

# 可选：Perplexity API
export PERPLEXITY_API_KEY="..."

# 可选：NIA API
export NIA_API_KEY="..."
```

---

### 快速参考摘要

| 仓库 | 技能 | 代理 | 钩子 |
|------|------|------|------|
| parcadei/continuous-claude-v3 | 109+ | 32 | 30 |

### 核心特色

1. **TLDR 代码分析** - 5 层分析节省 95% token
2. **会话连续性** - YAML 交接保持上下文
3. **记忆系统** - PostgreSQL + pgvector 持久化
4. **自然语言触发** - 无需记忆命令
5. **30 个钩子** - 自动注入上下文和验证
6. **32 个专业代理** - 编排复杂任务

---

*Generated with Claude Code | Skills Book v1.0 (Chinese Edition)*
