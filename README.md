# 🗂️ MCP Collection

> 个人 MCP 服务器收藏集 · Personal MCP Server Collection

一个精选的 MCP 服务器清单，收录在 Reasonix / Claude Desktop 等 MCP 客户端中实际安装和使用的 MCP 服务器。

---

## 📋 收藏列表

### 1️⃣ GitHub MCP Server

| 项目 | 内容 |
|---|---|
| 🏢 **官方** | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| ⭐ **Stars** | 30.5k |
| 🔤 **语言** | Go |
| 🧩 **工具数** | 43 个工具 / 19 个工具集 |

**功能覆盖：**
- 📝 Issues & Pull Requests — 创建、更新、管理
- 📂 仓库管理 — 代码搜索、文件操作
- 👥 用户管理 — 搜索、星标
- 🔒 安全 — Secret 扫描、安全公告
- 🤖 Copilot — 代码审查、Spaces
- 🚀 Actions — 工作流监控、Release 管理
- 💬 Discussions / Gist — 讨论和代码片段
- 🏷️ 标签 / 通知 / 项目

**安装方式（Windows）：**
```json
{
  "mcpServers": {
    "github": {
      "command": "C:\\path\\to\\github-mcp-server.exe",
      "args": ["stdio"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "your_token_here"
      }
    }
  }
}
```

> 📅 收录日期: 2026-06-08

---

## 🧩 技能来源收藏

### 1️⃣ anthropics/skills — Anthropic 官方技能库

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [anthropics/skills](https://github.com/anthropics/skills) |
| ⭐ **Stars** | 148k |
| 🧩 **技能数** | 17 个 |
| 📁 **已安装** | `algorithmic-art` / `brand-guidelines` / `canvas-design` / `claude-api` / `doc-coauthoring` / `docx` / `frontend-design` / `internal-comms` / `mcp-builder` / `pdf` / `pptx` / `skill-creator` / `slack-gif-creator` / `theme-factory` / `web-artifacts-builder` / `webapp-testing` / `xlsx` |

### 2️⃣ obra/superpowers — Agent 开发工作流框架

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [obra/superpowers](https://github.com/obra/superpowers) |
| ⭐ **Stars** | 221k |
| 🧩 **技能数** | 14 个 |
| 📁 **已安装** | `brainstorming` / `using-git-worktrees` / `writing-plans` / `subagent-driven-development` / `executing-plans` / `dispatching-parallel-agents` / `test-driven-development` / `requesting-code-review` / `receiving-code-review` / `finishing-a-development-branch` / `systematic-debugging` / `verification-before-completion` / `using-superpowers` / `writing-skills` |

### 3️⃣ OthmanAdi/planning-with-files — Manus 式文件规划

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) |
| ⭐ **Stars** | 22.9k |
| 🧩 **技能数** | 1 个（含中文版） |
| 📁 **已安装** | `planning-with-files-zh` |

### 4️⃣ vercel-labs/skills — Skills CLI 工具

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| ⭐ **Stars** | 21.7k |
| 🧩 **技能数** | 自带 `find-skills` 查找技能 |
| 📁 **已安装** | `find-skills` |
| 🔧 **作用** | `npx skills` CLI 管理工具，用于安装/管理/搜索技能 |

> 📅 收录日期: 2026-06-08

---

## ➕ 如何添加新 MCP

在 `servers/` 目录下创建 `.md` 文件，按以下模板填写：

```markdown
# [MCP 名称]

| 项目 | 内容 |
|---|---|
| **来源** | 链接 |
| **语言** | 实现语言 |
| **工具数** | n 个工具 |
| **用途** | 一句话描述 |
```

---

## 🔧 本机配置

**Reasonix 全局配置路径：**
`C:\Users\piggynj\AppData\Roaming\reasonix\config.toml`

**Claude Desktop 配置路径：**
`%APPDATA%\Claude\claude_desktop_config.json`