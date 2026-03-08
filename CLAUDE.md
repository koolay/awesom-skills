# CLAUDE.md

## 重要规则

### 添加 Skill 仓库时的同步要求

**每次添加新的 skill 仓库到 `SKILLS-BOOK.md` 后，必须同步更新 `README.md`：**

1. 在"主要 Skill 仓库"表格中添加新仓库条目，包括：
   - 仓库名称（链接）
   - 技能数量
   - 描述
   - 安装命令

2. 在"仓库详情"部分添加新仓库的详细信息，包括：
   - GitHub 链接
   - 技能类型
   - 代表技能（如适用）
   - 文档链接（如有）

3. 使用 git commit 提交更改，建议使用 conventional commits 格式：
   ```
   docs: add <repo-name> to README and SKILLS-BOOK
   ```

---

### 其他说明

- **book 使用中文作为主要语言**
- 代理设置（需要网络访问时）：
  ```bash
  export https_proxy=http://127.0.0.1:10080
  export http_proxy=http://127.0.0.1:10080
  export all_proxy=socks5://127.0.0.1:10080
  ```
