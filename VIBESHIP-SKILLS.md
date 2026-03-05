# vibeforge1111/vibeship-spawner-skills

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

## 四文件技能系统

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

---

## AI 与机器学习 (24 skills)

| 技能 | 描述 |
|------|------|
| `ai/llm-architect` | 设计 LLM 驱动的系统架构 |
| `ai/llm-fine-tuning` | 使用 LoRA、QLoRA、PEFT 进行模型微调 |
| `ai/prompt-engineering` | 高级提示词设计与优化 |
| `ai/embeddings-specialist` | 向量嵌入与语义搜索 |
| `ai/rag-engineer` | 检索增强生成 (RAG) 系统 |
| `ai/ml-memory` | AI 应用的记忆系统 |
| `ai/causal-scientist` | 因果推断与实验设计 |
| `ai/art-consistency` | 保持 AI 艺术中的角色/风格一致性 |
| `ai/nlp-advanced` | 命名实体识别、关系抽取 |
| `ai/computer-vision-deep` | 目标检测、分割、3D 视觉 |
| `ai/multimodal-ai` | 视觉 - 语言模型、跨模态系统 |
| `ai/model-optimization` | 量化、剪枝、知识蒸馏 |
| `ai/neural-architecture-search` | AutoML 与架构优化 |
| `ai/distributed-training` | 多 GPU 训练、DeepSpeed、FSDP |
| `ai/ml-ops` | 模型部署、监控、漂移检测 |
| `ai/ai-safety` | 对齐、红队测试、防护措施 |
| `ai/synthetic-data` | 大规模生成训练数据 |
| `ai/speech-recognition` | 自动语音识别系统、Whisper、语音处理 |
| `ai/recommender-systems` | 协同过滤、基于内容的推荐 |
| `ai/time-series-ml` | 预测、异常检测 |
| `ai/graph-neural-networks` | GNN 架构、节点分类 |
| `ai/reinforcement-learning` | 强化学习算法、策略优化 |
| `ai/federated-learning` | 隐私保护的分布式机器学习 |
| `ai/explainable-ai` | 模型可解释性、SHAP、LIME |

## AI 智能体与自动化 (23 skills)

| 技能 | 描述 |
|------|------|
| `ai-agents/autonomous-agents` | 构建独立工作的智能体 |
| `ai-agents/multi-agent-orchestration` | 协调多个 AI 智能体 |
| `ai-agents/agent-memory-systems` | 智能体的长期记忆 |
| `ai-agents/agent-tool-builder` | 创建智能体可使用的工具 |
| `ai-agents/browser-automation` | Playwright、Puppeteer、网页爬取 |
| `ai-agents/computer-use-agents` | 控制桌面/浏览器的智能体 |
| `ai-agents/voice-agents` | 基于语音的 AI 助手 |
| `ai-agents/workflow-automation` | n8n、Temporal、流程自动化 |
| `ai-agents/zapier-make-patterns` | 无代码自动化模式 |
| `ai-agents/agent-evaluation` | 测试与基准评估智能体 |
| `ai-agents/ai-product` | 构建 AI 驱动的产品 |
| `ai-agents/mcp-builder` | 模型上下文协议 (MCP) 服务器 |
| `ai-agents/langchain-patterns` | LangChain 最佳实践 |
| `ai-agents/llamaindex-patterns` | LlamaIndex 用于 RAG |
| `ai-agents/crewai-patterns` | CrewAI 多智能体系统 |
| `ai-agents/autogen-patterns` | 微软 AutoGen 智能体 |
| `ai-agents/agent-debugging` | 调试智能体行为 |
| `ai-agents/agent-security` | 保护智能体部署 |
| `ai-agents/agent-cost-optimization` | 降低 LLM 成本 |
| `ai-agents/agent-observability` | 监控智能体性能 |
| `ai-agents/conversational-ai` | 聊天机器人与对话系统 |
| `ai-agents/code-agents` | 编写和运行代码的智能体 |
| `ai-agents/research-agents` | 信息收集智能体 |

## AI 工具与实用程序 (12 skills)

| 技能 | 描述 |
|------|------|
| `ai-tools/ai-code-generation` | 代码生成最佳实践 |
| `ai-tools/ai-image-editing` | 使用 AI 进行图像编辑 |
| `ai-tools/ai-video-editing` | 使用 AI 进行视频处理 |
| `ai-tools/ai-audio-processing` | 音频增强与生成 |
| `ai-tools/ai-document-processing` | OCR、文档理解 |
| `ai-tools/ai-translation` | 机器翻译系统 |
| `ai-tools/ai-summarization` | 文本摘要技术 |
| `ai-tools/ai-content-moderation` | 内容安全与过滤 |
| `ai-tools/ai-search` | 语义搜索实现 |
| `ai-tools/ai-chatbot` | 聊天机器人开发模式 |
| `ai-tools/ai-writing-assistant` | 写作辅助工具 |
| `ai-tools/ai-data-extraction` | 结构化数据提取 |

## 游戏开发 (51 skills)

| 技能 | 描述 |
|------|------|
| `game-dev/unity-development` | Unity 游戏开发模式 |
| `game-dev/godot-development` | Godot 4、GDScript、最佳实践 |
| `game-dev/phaser-gamedev` | Phaser.js 网页游戏 |
| `game-dev/game-design-patterns` | 核心游戏设计原则 |
| `game-dev/multiplayer-netcode` | 多人游戏网络代码 |
| `game-dev/procedural-generation` | PCG 算法与系统 |
| `game-dev/game-audio` | 声音设计与实现 |
| `game-dev/game-ui-ux` | 游戏界面设计 |
| `game-dev/game-ai` | NPC 行为、寻路 |
| `game-dev/game-physics` | 物理引擎与模拟 |
| `game-dev/game-animation` | 动画系统与混合 |
| `game-dev/game-shaders` | 着色器编程、视觉特效 |
| `game-dev/game-optimization` | 性能优化 |
| `game-dev/game-monetization` | F2P、内购、战斗通行证 |
| `game-dev/game-analytics` | 玩家行为追踪 |
| `game-dev/game-localization` | 多语言支持 |
| `game-dev/game-accessibility` | 无障碍游戏设计 |
| `game-dev/game-narrative` | 故事系统、对话 |
| `game-dev/game-economy` | 虚拟经济、平衡 |
| `game-dev/game-testing` | 游戏 QA |
| `game-dev/3d-modeling` | 3D 建模、拓扑、UV 展开 |
| `game-dev/ai-game-art-generation` | AI 游戏资产生成 |
| `game-dev/animation-systems` | 实时游戏动画系统 |
| `game-dev/board-game-design` | 桌游设计 |
| `game-dev/card-game-design` | 集换式卡牌游戏设计 |
| `game-dev/character-design` | 角色设计 |
| `game-dev/combat-design` | 战斗系统设计 |
| `game-dev/concept-art` | 概念艺术 |
| `game-dev/creature-design` | 生物设计 |
| `game-dev/environment-art` | 环境美术 |
| `game-dev/game-ai-behavior` | 游戏 AI 行为系统 |
| `game-dev/game-ai-behavior-trees` | 行为树 AI |
| `game-dev/game-design` | 游戏设计核心 |
| `game-dev/game-design-core` | 核心循环设计 |
| `game-dev/game-development` | 游戏开发基础 |
| `game-dev/game-networking` | 游戏网络同步 |
| `game-dev/godot-llm-integration` | Godot LLM 集成 |
| `game-dev/level-design` | 关卡设计 |
| `game-dev/lighting-design` | 光照设计 |
| `game-dev/llm-game-development` | LLM 游戏开发工作流 |
| `game-dev/llm-npc-dialogue` | AI NPC 对话系统 |
| `game-dev/mobile-game-dev` | 移动端游戏开发 |
| `game-dev/narrative-design` | 叙事设计 |
| `game-dev/pixel-art` | 像素艺术 |
| `game-dev/pixel-art-sprites` | 像素精灵动画 |
| `game-dev/player-onboarding` | 玩家入门引导 |
| `game-dev/progression-systems` | 进度系统设计 |
| `game-dev/prompt-to-game` | 提示词生成游戏 |
| `game-dev/puzzle-design` | 谜题设计 |
| `game-dev/rigging-animation` | 绑定与动画 |
| `game-dev/roblox-development` | Roblox 游戏开发 |

## 营销与内容 (36 skills)

| 技能 | 描述 |
|------|------|
| `marketing/marketing-fundamentals` | 核心营销原则 |
| `marketing/content-strategy` | 内容规划与执行 |
| `marketing/seo` | 搜索引擎优化 |
| `marketing/copywriting` | 说服性写作 |
| `marketing/blog-writing` | 博客内容创作 |
| `marketing/ad-copywriting` | 广告文案 |
| `marketing/viral-marketing` | 病毒式增长策略 |
| `marketing/brand-storytelling` | 品牌叙事开发 |
| `marketing/ai-creative-director` | AI 驱动的创意指导 |
| `marketing/ai-image-generation` | 营销用 AI 图像创作 |
| `marketing/ai-video-generation` | AI 视频制作 |
| `marketing/ai-audio-production` | AI 音频与配音 |
| `marketing/ai-content-analytics` | AI 驱动的内容分析 |
| `marketing/ai-brand-kit` | AI 品牌资产生成 |
| `marketing/ai-localization` | AI 翻译与本地化 |
| `marketing/digital-humans` | 虚拟网红、虚拟化身 |
| `marketing/voiceover` | 配音制作 |
| `marketing/video-production` | 视频内容创作 |
| `marketing/motion-graphics` | 动画内容 |
| `marketing/social-media-strategy` | 社交平台策略 |
| `marketing/email-marketing` | 邮件营销活动 |
| `marketing/influencer-marketing` | 网红合作 |
| `marketing/growth-hacking` | 快速增长策略 |
| `marketing/conversion-optimization` | 转化率优化最佳实践 |
| `marketing/landing-page-copy` | 高转化落地页 |
| `marketing/product-launch` | 发布策略 |
| `marketing/saas-marketing` | SaaS 增长手册 |
| `marketing/developer-marketing` | 面向开发者的营销 |
| `marketing/ai-ad-creative` | AI 广告创意与效果营销 |
| `marketing/ai-content-qa` | AI 内容质量保证与审核 |
| `marketing/ai-trend-alchemy` | 趋势预测与 AI 内容生成 |
| `marketing/ai-visual-effects` | AI 视觉特效与后期制作 |
| `marketing/ai-workflow-automation` | AI 内容工作流自动化 |
| `marketing/ai-world-building` | AI 品牌世界构建 |
| `marketing/creative-communications` | 创意资产制作与传播 |
| `marketing/explainer-videos` | 解释性视频策略 |

## 第三方集成 (25 skills)

| 技能 | 描述 |
|------|------|
| `integrations/stripe` | Stripe 支付集成 |
| `integrations/aws-serverless` | AWS Lambda、API Gateway 无服务器架构 |
| `integrations/gcp-services` | Google Cloud Platform 服务 |
| `integrations/azure-services` | Microsoft Azure 服务 |
| `integrations/supabase` | Supabase 后端服务 |
| `integrations/firebase` | Firebase 服务集成 |
| `integrations/twilio` | 短信、语音、视频通信 |
| `integrations/sendgrid` | 邮件投递服务 |
| `integrations/discord-bot` | Discord 机器人开发 |
| `integrations/slack-bot` | Slack 集成开发 |
| `integrations/github-actions` | GitHub Actions CI/CD |
| `integrations/vercel` | Vercel 部署平台 |
| `integrations/cloudflare` | Cloudflare Workers、Pages |
| `integrations/openai-api` | OpenAI API 集成 |
| `integrations/anthropic-api` | Claude API 集成 |
| `integrations/plaid` | 银行服务集成 |
| `integrations/shopify` | 电商系统集成 |
| `integrations/notion-api` | Notion 集成开发 |
| `integrations/airtable` | Airtable 数据集成 |
| `integrations/hubspot` | HubSpot CRM 集成 |
| `integrations/salesforce` | Salesforce CRM 集成 |
| `integrations/zapier-integration` | Zapier 应用开发 |
| `integrations/oauth-providers` | 社交账号登录集成 |
| `integrations/analytics-platforms` | 分析平台集成 |
| `integrations/payment-processors` | 支付网关集成模式 |

## 战略与商业 (24 skills)

| 技能 | 描述 |
|------|------|
| `strategy/product-strategy` | 产品愿景与路线图 |
| `strategy/growth-strategy` | 规模化战略 |
| `strategy/go-to-market` | 上市策略规划 |
| `strategy/competitive-intelligence` | 市场分析 |
| `strategy/pricing-strategy` | 定价优化 |
| `strategy/fundraising-strategy` | 融资策略 |
| `strategy/business-model` | 商业模式设计 |
| `strategy/market-research` | 客户研究 |
| `strategy/positioning` | 品牌定位 |
| `strategy/partnership-strategy` | 战略合作伙伴关系 |
| `strategy/expansion-strategy` | 地域/市场扩张 |
| `strategy/pivot-strategy` | 何时及如何转型 |
| `strategy/exit-strategy` | 并购、上市规划 |
| `strategy/investor-relations` | 投资者管理 |
| `strategy/board-management` | 董事会动态 |
| `strategy/okr-strategy` | OKR 实施 |
| `strategy/resource-allocation` | 预算与资源规划 |
| `strategy/risk-management` | 业务风险评估 |
| `strategy/innovation-strategy` | 研发与创新 |
| `strategy/platform-strategy` | 平台商业模式 |
| `strategy/ecosystem-strategy` | 构建生态系统 |
| `strategy/data-strategy` | 数据作为战略资产 |
| `strategy/talent-strategy` | 招聘与留任 |
| `strategy/culture-strategy` | 构建公司文化 |

## 创意与趣味 (23 skills)

| 技能 | 描述 |
|------|------|
| `creative/meme-engineering` | 创作病毒式梗图 |
| `creative/easter-egg-design` | 隐藏彩蛋设计 |
| `creative/gamification-loops` | 游戏化参与机制 |
| `creative/viral-hooks` | 病毒式内容钩子 |
| `creative/absurdist-voice` | 非传统品牌声音 |
| `creative/lore-building` | 世界观与故事创作 |
| `creative/cliffhanger-craft` | 悬念与参与度设计 |
| `creative/roast-writing` | 幽默式吐槽写作 |
| `creative/anti-marketing` | 反文化营销 |
| `creative/cultural-remix` | 文化元素混搭 |
| `creative/side-project-shipping` | 快速发布副业项目 |
| `creative/tech-debt-negotiation` | 技术债务管理 |
| `creative/documentation-that-slaps` | 引人入胜的文档写作 |
| `creative/code-review-diplomacy` | 建设性代码审查 |
| `creative/legacy-archaeology` | 旧代码库考古 |
| `creative/scope-creep-defense` | 项目范围保护 |
| `creative/demo-day-theater` | 惊艳演示技巧 |
| `creative/incident-postmortem` | 从失败中学习 |
| `creative/regex-whisperer` | 正则表达式大师 |
| `creative/git-time-travel` | Git 高级时间旅行技巧 |
| `creative/generative-art` | 代码生成艺术 |
| `creative/demoscene-coding` | Demo 效果编程 |
| `creative/hand-gesture-recognition` | 手势识别界面 |

## DevOps 与基础设施 (22 skills)

| 技能 | 描述 |
|------|------|
| `devops/devops` | 核心 DevOps 实践 |
| `devops/infra-architect` | 基础设施架构设计 |
| `devops/observability-sre` | 监控与告警 |
| `devops/kubernetes` | K8s 编排 |
| `devops/docker` | 容器最佳实践 |
| `devops/terraform` | 基础设施即代码 |
| `devops/ci-cd` | 流水线设计 |
| `devops/gitops` | GitOps 工作流 |
| `devops/cloud-cost` | 成本优化 |
| `devops/incident-management` | 事件响应 |
| `devops/chaos-engineering` | 弹性测试 |
| `devops/service-mesh` | Istio, Linkerd |
| `devops/secrets-management` | Vault, 密钥管理 |
| `devops/logging` | 集中式日志 |
| `devops/metrics` | 指标与仪表板 |
| `devops/tracing` | 分布式追踪 |
| `devops/load-balancing` | 流量管理 |
| `devops/cdn` | 内容分发网络 |
| `devops/dns` | DNS 管理 |
| `devops/ssl-tls` | 证书管理 |
| `devops/backup-recovery` | 灾难恢复 |
| `devops/compliance-devops` | 安全合规 |

## 后端与 API (21 skills)

| 技能 | 描述 |
|------|------|
| `backend/backend` | 核心后端开发 |
| `backend/api-designer` | API 设计模式 |
| `backend/microservices` | 微服务架构 |
| `backend/graphql` | GraphQL APIs |
| `backend/grpc` | gRPC 服务 |
| `backend/event-driven` | 事件驱动架构 |
| `backend/queue-systems` | 消息队列，Kafka |
| `backend/caching` | Redis, Memcached 模式 |
| `backend/rate-limiting` | API 速率限制 |
| `backend/webhooks` | Webhook 实现 |
| `backend/background-jobs` | 作业处理 |
| `backend/file-upload` | 文件处理 |
| `backend/search` | 搜索实现 |
| `backend/real-time` | WebSockets, SSE |
| `backend/api-versioning` | API 版本控制策略 |
| `backend/pagination` | 分页模式 |
| `backend/error-handling` | 错误处理模式 |
| `backend/logging-backend` | 后端日志 |
| `backend/testing-backend` | 后端测试 |
| `backend/performance` | 后端优化 |
| `backend/security-backend` | 后端安全 |

## 区块链与 Web3 (20 skills)

| 技能 | 描述 |
|------|------|
| `blockchain/smart-contract-auditor` | 安全审计 |
| `blockchain/defi-architect` | DeFi 协议设计 |
| `blockchain/nft-engineer` | NFT 开发 |
| `blockchain/evm-deep-dive` | EVM 内部原理 |
| `blockchain/solana-development` | Solana 程序开发 |
| `blockchain/web3-gaming` | 区块链游戏 |
| `blockchain/tokenomics` | 代币经济学 |
| `blockchain/dao-governance` | DAO 治理结构 |
| `blockchain/bridge-protocols` | 跨链桥协议 |
| `blockchain/layer2-scaling` | 二层扩展方案 |
| `blockchain/wallet-integration` | 钱包集成 |
| `blockchain/gas-optimization` | Gas 优化 |
| `blockchain/upgradeable-contracts` | 可升级合约（代理模式） |
| `blockchain/oracles` | 预言机（Chainlink、价格馈送） |
| `blockchain/yield-farming` | 收益耕作策略 |
| `blockchain/amm-design` | 自动做市商（AMM）机制 |
| `blockchain/lending-protocols` | 借贷协议 |
| `blockchain/staking-systems` | 质押机制 |
| `blockchain/privacy-chains` | 隐私区块链方案 |
| `blockchain/blockchain-indexing` | 区块链索引（The Graph、索引器） |

## 安全与认证 (13 skills)

| 技能 | 描述 |
|------|------|
| `security/security` | 核心安全实践 |
| `security/auth-specialist` | 认证系统 |
| `security/oauth-oidc` | OAuth 2.0, OpenID Connect |
| `security/jwt-security` | JWT 最佳实践 |
| `security/api-security` | API 安全模式 |
| `security/web-security` | OWASP Top 10 |
| `security/cryptography` | 加密，哈希 |
| `security/penetration-testing` | 安全测试 |
| `security/security-headers` | HTTP 安全头 |
| `security/cors` | CORS 配置 |
| `security/csrf-protection` | CSRF 防护 |
| `security/input-validation` | 输入验证 |
| `security/secrets-handling` | 安全密钥管理 |

## 设计与用户体验 (12 skills)

| 技能 | 描述 |
|------|------|
| `design/ui-design` | 用户界面设计 |
| `design/ux-design` | 用户体验设计 |
| `design/branding` | 品牌识别 |
| `design/landing-page-design` | 落地页设计 |
| `design/design-systems` | 组件库/设计系统 |
| `design/accessibility-design` | 无障碍设计 |
| `design/mobile-design` | 移动端 UX 模式 |
| `design/animation-design` | 动效设计 |
| `design/typography` | 字体选择与搭配 |
| `design/color-theory` | 色彩系统 |
| `design/iconography` | 图标设计 |
| `design/illustration` | 定制插画 |

## 框架 (12 skills)

| 技能 | 描述 |
|------|------|
| `frameworks/nextjs-app-router` | Next.js 14+ App Router |
| `frameworks/react-patterns` | React 最佳实践 |
| `frameworks/supabase-backend` | Supabase 集成 |
| `frameworks/sveltekit` | SvelteKit 开发 |
| `frameworks/tailwind-ui` | Tailwind CSS 模式 |
| `frameworks/typescript-strict` | 严格 TypeScript |
| `frameworks/remix` | Remix 框架 |
| `frameworks/astro` | Astro 静态站点 |
| `frameworks/vue-nuxt` | Vue 和 Nuxt |
| `frameworks/solid-js` | SolidJS 模式 |
| `frameworks/htmx` | HTMX 超媒体 |
| `frameworks/electron` | 桌面应用开发 |

## 社区建设 (11 skills)

| 技能 | 描述 |
|------|------|
| `community/community-strategy` | 社区规划与愿景 |
| `community/community-operations` | 日常社区管理 |
| `community/community-growth` | 有机社区增长 |
| `community/community-analytics` | 衡量社区健康度 |
| `community/discord-mastery` | Discord 服务器管理 |
| `community/telegram-mastery` | Telegram 社区建设 |
| `community/social-community` | 社交媒体社区 |
| `community/developer-community` | DevRel 与开发者社区 |
| `community/ambassador-programs` | 大使与倡导者计划 |
| `community/web3-community` | 加密货币/Web3 社区建设 |
| `community/community-tooling` | 社区工具与平台 |

## 数据与数据库 (11 skills)

| 技能 | 描述 |
|------|------|
| `data/postgres-wizard` | PostgreSQL 大师 |
| `data/redis-specialist` | Redis 模式专家 |
| `data/vector-specialist` | 向量数据库专家 |
| `data/data-engineer` | 数据管道工程师 |
| `data/graph-engineer` | 图数据库工程师 |
| `data/temporal-craftsman` | 时间序列数据处理 |
| `data/data-modeling` | 模式设计 |
| `data/query-optimization` | 查询性能优化 |
| `data/data-migration` | 数据迁移策略 |
| `data/data-warehousing` | 分析型数据库 |
| `data/data-quality` | 数据验证 |

## 创作者工具 (11 skills)

| 技能 | 描述 |
|------|------|
| `maker/viral-generator-builder` | 构建可病毒传播的生成器 |
| `maker/scroll-experience` | GSAP/Framer 滚动驱动叙事体验 |
| `maker/interactive-portfolio` | 高转化率互动作品集 |
| `maker/3d-web-experience` | Three.js、React Three Fiber、Spline 3D 网页体验 |
| `maker/telegram-bot-builder` | 带变现功能的 Telegram 机器人 |
| `maker/telegram-mini-app` | TON Connect、Telegram 迷你应用 |
| `maker/micro-saas-launcher` | 2 周 MVP 到付费客户 |
| `maker/browser-extension-builder` | Chrome/Firefox MV3 扩展开发 |
| `maker/ai-wrapper-product` | AI API 封装产品与成本管理 |
| `maker/notion-template-business` | Notion 模板设计与销售 |
| `maker/personal-tool-builder` | 解决自身痛点方法论 |

## 思维与决策 (10 skills)

| 技能 | 描述 |
|------|------|
| `mind/debugging-master` | 系统化调试方法 |
| `mind/decision-maker` | 决策框架 |
| `mind/system-designer` | 系统设计思维 |
| `mind/refactoring-guide` | 安全重构策略 |
| `mind/performance-thinker` | 性能优化思维 |
| `mind/tech-debt-manager` | 技术债务管理 |
| `mind/test-strategist` | 测试策略 |
| `mind/code-quality` | 代码质量原则 |
| `mind/incident-responder` | 事件响应 |
| `mind/technical-writer` | 技术文档写作 |

## 开发工具 (9 skills)

| 技能 | 描述 |
|------|------|
| `development/docs-engineer` | 文档系统 |
| `development/performance-hunter` | 性能优化 |
| `development/monorepo` | Monorepo 管理 |
| `development/dependency-management` | 包管理 |
| `development/code-generation` | 代码生成器 |
| `development/cli-development` | CLI 工具开发 |
| `development/sdk-development` | SDK 设计 |
| `development/api-client` | API 客户端模式 |
| `development/debugging-tools` | 调试工具 |

## 前端与移动端 (8 skills)

| 技能 | 描述 |
|------|------|
| `frontend/frontend` | 核心前端开发 |
| `frontend/state-management` | 状态管理模式 |
| `frontend/forms` | 表单处理 |
| `frontend/responsive-design` | 响应式布局 |
| `frontend/performance-frontend` | 前端性能优化 |
| `frontend/react-native` | React Native 移动开发 |
| `frontend/flutter` | Flutter 开发 |
| `frontend/pwa` | 渐进式 Web 应用 |

## 测试与质量保证 (8 skills)

| 技能 | 描述 |
|------|------|
| `testing/test-architect` | 测试架构 |
| `testing/code-reviewer` | 代码审查实践 |
| `testing/chaos-engineer` | 混沌测试 |
| `testing/e2e-testing` | 端到端测试 |
| `testing/unit-testing` | 单元测试模式 |
| `testing/integration-testing` | 集成测试 |
| `testing/performance-testing` | 负载测试 |
| `testing/visual-regression` | 视觉回归测试 |

## 教育与学习 (7 skills)

| 技能 | 描述 |
|------|------|
| `education/course-creation` | 创建和构建在线课程 |
| `education/live-education` | 直播教学、网络研讨会、工作坊 |
| `education/education-business` | 教育产品变现 |
| `education/learning-experience` | 学习设计与教学法 |
| `education/education-platforms` | 平台选择与设置 |
| `education/ai-for-learning` | AI 辅导与自适应学习 |
| `education/student-success` | 学生成果与留存 |

## 产品管理 (7 skills)

| 技能 | 描述 |
|------|------|
| `product/product-management` | 核心产品管理技能 |
| `product/a/b-testing` | 实验测试 |
| `product/analytics` | 产品分析 |
| `product/user-research` | 用户研究 |
| `product/roadmapping` | 路线图规划 |
| `product/prioritization` | 功能优先级排序 |
| `product/metrics` | 产品指标 |

## 生物技术与生命科学 (6 skills)

| 技能 | 描述 |
|------|------|
| `biotech/genomics-pipelines` | 生物信息学流程 |
| `biotech/drug-discovery-informatics` | 药物发现机器学习 |
| `biotech/lab-automation` | 实验室自动化系统 |
| `biotech/clinical-data` | 临床数据管理 |
| `biotech/regulatory-compliance` | FDA、EMA 合规 |
| `biotech/bioprocess` | 生物工艺优化 |

## 企业架构 (6 skills)

| 技能 | 描述 |
|------|------|
| `enterprise/compliance-automation` | 自动化合规 |
| `enterprise/data-governance` | 数据治理 |
| `enterprise/disaster-recovery` | 灾难恢复规划 |
| `enterprise/enterprise-architecture` | 企业架构框架 |
| `enterprise/integration-patterns` | 企业集成模式 |
| `enterprise/multi-tenancy` | 多租户系统 |

## 金融与金融科技 (6 skills)

| 技能 | 描述 |
|------|------|
| `finance/algorithmic-trading` | 交易系统 |
| `finance/blockchain-defi` | DeFi 协议 |
| `finance/derivatives-pricing` | 衍生品定价、期权希腊值 |
| `finance/fintech-integration` | 金融 API |
| `finance/portfolio-optimization` | 投资组合理论 |
| `finance/risk-modeling` | 风险评估 |

## 硬件与机器人 (6 skills)

| 技能 | 描述 |
|------|------|
| `hardware/embedded-systems` | 嵌入式开发 |
| `hardware/ros2-robotics` | ROS2 机器人 |
| `hardware/fpga-development` | FPGA 设计 |
| `hardware/sensor-fusion` | 传感器融合 |
| `hardware/motor-control` | 电机系统 |
| `hardware/pcb-design` | PCB 布局 |

## 交易与量化 (6 skills)

| 技能 | 描述 |
|------|------|
| `trading/execution-algorithms` | 执行算法 |
| `trading/quantitative-research` | 量化研究 |
| `trading/risk-management-trading` | 交易风险管理 |
| `trading/sentiment-analysis-trading` | 市场情绪分析 |
| `trading/technical-analysis` | 图表形态分析 |
| `trading/trading-psychology` | 交易心态 |

## 气候与可持续发展 (5 skills)

| 技能 | 描述 |
|------|------|
| `climate/carbon-accounting` | 碳足迹追踪 |
| `climate/sustainability-metrics` | ESG 指标 |
| `climate/energy-optimization` | 能源效率 |
| `climate/climate-modeling` | 气候模型 |
| `climate/circular-economy` | 循环经济设计 |

## 沟通与表达 (5 skills)

| 技能 | 描述 |
|------|------|
| `communications/dev-communications` | 开发者沟通 |
| `communications/crisis-comms` | 危机管理 |
| `communications/stakeholder-comms` | 利益相关者更新 |
| `communications/technical-presentations` | 技术演示 |
| `communications/investor-updates` | 投资者沟通 |

## 法律与合规 (5 skills)

| 技能 | 描述 |
|------|------|
| `legal/gdpr-privacy` | GDPR 合规 |
| `legal/contract-analysis` | 合同审查 |
| `legal/patent-drafting` | 专利申请 |
| `legal/sox-compliance` | SOX 合规要求 |
| `legal/export-control` | 出口管制法规 |

## 仿真与建模 (5 skills)

| 技能 | 描述 |
|------|------|
| `simulation/monte-carlo` | 蒙特卡洛方法 |
| `simulation/digital-twin` | 数字孪生 |
| `simulation/physics-simulation` | 物理引擎 |
| `simulation/agent-based-modeling` | 基于代理的模型 |
| `simulation/system-dynamics` | 系统动力学 |

## 航天与航空 (5 skills)

| 技能 | 描述 |
|------|------|
| `space/orbital-mechanics` | 轨道计算 |
| `space/mission-planning` | 任务设计 |
| `space/ground-station-ops` | 地面站运营 |
| `space/spacecraft-systems` | 航天器工程 |
| `space/space-data` | 太空数据处理 |

## 科学与研究 (4 skills)

| 技能 | 描述 |
|------|------|
| `science/experimental-design` | 实验规划 |
| `science/statistics` | 统计分析 |
| `science/research-methodology` | 研究方法 |
| `science/data-visualization` | 科学可视化 |

## 初创公司与创始人 (3 skills)

| 技能 | 描述 |
|------|------|
| `startup/yc-playbook` | YC 最佳实践 |
| `startup/founder-mode` | 创始人思维模式 |
| `startup/burn-rate-management` | 财务跑道管理 |

---

## 技能包 (Skill Packs)

| 技能包 | 描述 |
|--------|------|
| `essentials` | 构建应用的核心技能（自动安装） |
| `agents` | 自主代理和自动化 |
| `community` | 社区建设和管理 |
| `education` | 课程创建和在线学习 |
| `maker` | 病毒式工具、机器人、扩展、SaaS |
| `enterprise` | 合规和治理 |
| `finance` | 交易和金融科技 |
| `mind` | 调试和决策 |
| `specialized` | 生物技术、太空、气候、硬件 |
| `complete` | 全部 462 个技能 |

## 使用技能

### 在 Claude 中加载技能
```bash
# 让 Claude 读取技能文件
Read: ~/.spawner/skills/maker/micro-saas-launcher/skill.yaml
```

### 使用 MCP 工具
```bash
# 搜索技能
spawner_skills({ query: "telegram bot" })

# 加载特定技能
spawner_load({ skill_id: "telegram-bot-builder" })
```

### 在线浏览
访问 **[spawner.vibeship.co/skills](https://spawner.vibeship.co/skills)** 查看交互式目录。

---

*最后更新：2025-12-31 | 35 个类别共 462 个技能*
