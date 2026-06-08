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
