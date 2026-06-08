# GitHub MCP Server

| 项目 | 内容 |
|---|---|
| 🏢 **官方仓库** | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| ⭐ **Stars** | 30.5k |
| 🔤 **实现语言** | Go |
| 📦 **最新版本** | v1.2.0 |
| 🧩 **工具数量** | 43 个 |
| 📅 **收录日期** | 2026-06-08 |

## 📋 功能工具集

| 工具集 | 用途 |
|---|---|
| `actions` | GitHub Actions 工作流管理 |
| `code_security` | 代码安全告警 |
| `copilot` | Copilot 代码审查、Spaces |
| `context` | 用户/团队基本信息 |
| `dependabot` | Dependabot 告警管理 |
| `discussions` | 仓库讨论 |
| `gists` | 代码片段管理 |
| `git` | Git 操作（分支、标签等） |
| `issues` | Issue 创建、读取、更新 |
| `labels` | 标签管理 |
| `notifications` | 通知查看 |
| `orgs` | 组织管理 |
| `projects` | 项目看板 |
| `pull_requests` | Pull Request 完整操作 |
| `repos` | 仓库管理、搜索 |
| `secret_protection` | Secret 扫描 |
| `security_advisories` | 安全公告 |
| `stargazers` | 星标管理 |
| `users` | 用户搜索 |

## 🚀 安装方式

### 方式 1：二进制下载（推荐，无需 Docker/Go）

从 [Releases](https://github.com/github/github-mcp-server/releases) 下载对应系统架构的压缩包：

| 系统 | 下载文件 |
|---|---|
| Windows x86_64 | `github-mcp-server_Windows_x86_64.zip` |
| Windows arm64 | `github-mcp-server_Windows_arm64.zip` |
| macOS Intel | `github-mcp-server_Darwin_x86_64.tar.gz` |
| macOS Apple Silicon | `github-mcp-server_Darwin_arm64.tar.gz` |
| Linux x86_64 | `github-mcp-server_Linux_x86_64.tar.gz` |

### 方式 2：Docker

```bash
docker run -i --rm -e GITHUB_PERSONAL_ACCESS_TOKEN ghcr.io/github/github-mcp-server
```

### 方式 3：源码编译

```bash
git clone https://github.com/github/github-mcp-server.git
cd github-mcp-server
go build -o github-mcp-server ./cmd/github-mcp-server
```

## 🔧 配置示例

### Reasonix（全局配置）

```toml
[[plugins]]
name    = "github"
command = "C:\\path\\to\\github-mcp-server.exe"
args    = ["stdio"]
env     = { GITHUB_PERSONAL_ACCESS_TOKEN = "your_token_here" }
```

### Claude Desktop

```json
{
  "mcpServers": {
    "github": {
      "command": "C:\\path\\to\\github-mcp-server.exe",
      "args": ["stdio"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "<YOUR_TOKEN>"
      }
    }
  }
}
```

### VS Code（远程版，无需下载）

```json
{
  "servers": {
    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/"
    }
  }
}
```

## ⚙️ 高级选项

| 参数 | 说明 |
|---|---|
| `--read-only` | 只读模式，禁止修改操作 |
| `--toolsets=issues,pull_requests` | 只启用指定工具集 |
| `--lockdown-mode` | 锁定模式，限制公开仓库内容范围 |
| `--gh-host=https://ghe.example.com` | 连接 GitHub Enterprise |
| `--insiders` | 启用内测新功能 |

## 🔑 权限要求

需要一个 **GitHub Personal Access Token**：
- **Fine-grained PAT** ✅ 推荐（更安全，可限定到具体仓库）
- **Classic PAT** 勾选 `repo` 范围

> ⚠️ 细粒度 PAT 不支持 `--read-only` 模式？不需要——在权限设置中只给 `read` 级别即可实现同样效果。
