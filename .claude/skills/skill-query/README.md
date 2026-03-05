---
name: skill-query
description: "查找和安装技能的快速参考指南。优先搜索本地项目中的技能，再查询 SKILLS-BOOK.md 和 VIBESHIP-SKILLS.md。当用户询问技能相关帮助时触发。"
---

# Skill Query - 技能查询指南

## 目的

帮助快速查找和安装需要的技能，提供：
- 优先搜索本地项目中的技能和技能配置文件
- 技能搜索方法
- 安装命令参考
- 技能来源仓库信息
- 常用技能示例

## 触发时机

当用户询问：
- "如何安装 X 技能"
- "有什么 X 相关的技能"
- "查找 X 技能"
- "skill 怎么安装"
- "如何搜索技能"
- "@skill-query"

## 搜索流程（优先本地）

### 第一步：搜索本地项目（优先）
```bash
# 搜索项目中的技能相关文件
grep -r "关键词" .claude/skills/ SKILLS-BOOK.md VIBESHIP-SKILLS.md README.md 2>/dev/null

# 搜索已安装的技能
ls -la .claude/skills/
ls -la .agents/skills/

# 搜索技能配置文件
find . -name "*.skill" -o -name "skill.yaml" 2>/dev/null
```

### 第二步：搜索手册文件
```bash
grep -ri "关键词" SKILLS-BOOK.md VIBESHIP-SKILLS.md
```

### 第三步：提供安装命令
```bash
npx skills add <仓库地址> --skill <技能名称>
```

## 技能来源仓库

| 仓库 | 技能数 | 安装命令 |
|------|--------|----------|
| softaworks/agent-toolkit | 50+ | `npx skills add softaworks/agent-toolkit` |
| sickn33/antigravity-awesome-skills | 960+ | `npx skills add sickn33/antigravity-awesome-skills` |
| vibeforge1111/vibeship-spawner-skills | 462+ | `npx github:vibeforge1111/vibeship-spawner-skills install` |

## 常用技能示例

### Git 相关
```bash
npx skills add softaworks/agent-toolkit --skill commit-work
```

### AI/LLM 相关
```bash
npx skills add sickn33/antigravity-awesome-skills --skill prompt-engineer
npx skills add sickn33/antigravity-awesome-skills --skill rag-engineer
```

### 前端开发
```bash
npx skills add sickn33/antigravity-awesome-skills --skill react-best-practices
npx skills add sickn33/antigravity-awesome-skills --skill typescript-expert
```

### 测试相关
```bash
npx skills add sickn33/antigravity-awesome-skills --skill test-driven-development
npx skills add sickn33/antigravity-awesome-skills --skill playwright-skill
```

## 安装命令格式

```bash
npx skills add <仓库地址> --skill <技能名称>
```

## 技巧

1. 技能名称使用小写 + 连字符格式，如 `commit-work`
2. **优先搜索本地**：先查 `.claude/skills/` 和项目文档
3. 查看技能详情：安装前在 `SKILLS-BOOK.md` 中查看描述
4. 批量安装：某些仓库支持技能包一次性安装
