# Skill 查询使用指南

快速查找和安装你需要的技能。

---

## 🔍 如何查找技能

### 方法 1: 使用 Grep 搜索

```bash
# 按关键词搜索技能
grep -r "技能关键词" SKILLS-BOOK.md VIBESHIP-SKILLS.md

# 示例：搜索 AI 相关技能
grep -i "ai" SKILLS-BOOK.md

# 示例：搜索 git 相关技能
grep -i "git" VIBESHIP-SKILLS.md
```

### 方法 2: 浏览分类目录

打开 `SKILLS-BOOK.md` 或 `VIBESHIP-SKILLS.md` 文件，按类别浏览：

| 类别 | 描述 | 技能数 |
|------|------|--------|
| AI & ML | LLM、RAG、机器学习 | 59 |
| AI Agents | 自主代理、多代理编排 | 23 |
| Game Dev | Unity、Godot、游戏设计 | 51 |
| Marketing | 内容策略、SEO、病毒营销 | 36 |
| DevOps | K8s、Docker、CI/CD | 22 |
| Backend | API、微服务、缓存 | 21 |
| Security | OAuth、加密、渗透测试 | 13 |
| Frontend | React、状态管理、PWA | 8 |
| Testing | TDD、E2E、性能测试 | 8 |

---

## 📦 如何安装技能

使用 `skills.sh` 工具安装：

```bash
# 基本安装命令
npx skills add <仓库地址> --skill <技能名称>

# 示例：安装 commit-work 技能
npx skills add softaworks/agent-toolkit --skill commit-work

# 示例：安装 typescript-expert 技能
npx skills add sickn33/antigravity-awesome-skills --skill typescript-expert
```

---

## 📚 技能来源仓库

| 仓库 | 技能数 | 安装命令 |
|------|--------|----------|
| softaworks/agent-toolkit | 50+ | `npx skills add softaworks/agent-toolkit` |
| sickn33/antigravity-awesome-skills | 960+ | `npx skills add sickn33/antigravity-awesome-skills` |
| vibeforge1111/vibeship-spawner-skills | 462+ | `npx github:vibeforge1111/vibeship-spawner-skills install` |

---

## 🔎 常用技能示例

### Git 相关
```bash
# 高质量 git 提交
npx skills add softaworks/agent-toolkit --skill commit-work
```

### AI/LLM 相关
```bash
# 提示词工程
npx skills add sickn33/antigravity-awesome-skills --skill prompt-engineer

# RAG 系统开发
npx skills add sickn33/antigravity-awesome-skills --skill rag-engineer
```

### 前端开发
```bash
# React 最佳实践
npx skills add sickn33/antigravity-awesome-skills --skill react-best-practices

# TypeScript 专家
npx skills add sickn33/antigravity-awesome-skills --skill typescript-expert
```

### 测试相关
```bash
# 测试驱动开发
npx skills add sickn33/antigravity-awesome-skills --skill test-driven-development

# Playwright 测试
npx skills add sickn33/antigravity-awesome-skills --skill playwright-skill
```

---

## 💡 技巧

1. **技能名称通常是小写 + 连字符格式**，如 `commit-work`、`test-driven-development`

2. **先搜索再安装**：使用 `grep` 确认技能名称和所在仓库

3. **查看技能详情**：安装前可以在 `SKILLS-BOOK.md` 中查看技能的详细描述

4. **批量安装**：某些仓库支持技能包（skill packs）一次性安装多个技能

---

## ❓ 常见问题

**Q: 如何知道某个技能在哪个仓库？**
A: 在 `SKILLS-BOOK.md` 和 `VIBESHIP-SKILLS.md` 中使用 grep 搜索技能名称

**Q: 安装失败怎么办？**
A: 确认技能名称正确，检查网络连接，或尝试更新 skills 工具

**Q: 如何更新已安装的技能？**
A: 重新运行安装命令，或查看具体仓库的更新说明

---

*最后更新：2026-03-05*
