# Skill Query - 技能查询指南

一个帮助用户快速查找和安装技能的参考工具。

## 核心原则

**优先搜索本地项目，再查询外部资源**

## 目的

本技能帮助开发者：
- 优先搜索本地项目中的技能和配置
- 快速定位需要的技能
- 获取正确的安装命令
- 了解技能来源和最佳实践

## 触发短语

- "帮我找 X 技能"
- "如何安装 X 技能"
- "有什么 X 相关的技能"
- "查找技能"
- "skill 查询"
- "@skill-query"

## 工作流程（本地优先）

### 1. 搜索本地项目（必须第一步）
```bash
# 搜索 .claude/skills/ 目录
ls -la .claude/skills/

# 搜索项目中的技能相关文件
grep -ri "关键词" .claude/skills/ SKILLS-BOOK.md VIBESHIP-SKILLS.md README.md
```

### 2. 如果本地没有找到，搜索技能手册
```bash
grep -ri "关键词" SKILLS-BOOK.md VIBESHIP-SKILLS.md
```

### 3. 提供安装命令
```bash
npx skills add <仓库地址> --skill <技能名称>
```

## 本地搜索优先级

1. **`.claude/skills/`** - 当前项目已安装的技能
2. **`.agents/skills/`** - 通用技能目录
3. **`SKILLS-BOOK.md`** - 本地技能手册
4. **`VIBESHIP-SKILLS.md`** - Vibeship 技能列表
5. **外部仓库** - 最后才考虑从外部安装

## 技能仓库

| 仓库 | 技能数 | 特点 |
|------|--------|------|
| softaworks/agent-toolkit | 50+ | 精品技能，开发/文档/工作流 |
| sickn33/antigravity-awesome-skills | 960+ | 最全面的技能集合 |
| vibeforge1111/vibeship-spawner-skills | 462+ | 4 文件结构，带验证 |

## 输出内容

提供：
- 本地是否有相关技能（优先）
- 技能名称和描述
- 来源仓库
- 安装命令
