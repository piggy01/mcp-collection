# vercel-labs/skills — npx skills CLI 管理工具

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |
| ⭐ **Stars** | 21.7k |
| 🍴 **Forks** | 1.7k |
| 📋 **最新版本** | v1.5.10 |
| 🔤 **语言** | TypeScript |
| 📅 **收录日期** | 2026-06-08 |

## 📝 简介

**这不是一个技能仓库，而是一个 CLI 工具。** `npx skills` 是一个跨 Agent 的技能安装/管理/搜索工具，支持 OpenCode、Claude Code、Codex、Cursor 等 **67 种** AI 编码 Agent。

## 🧩 技能清单

| # | 技能名 | 说明 |
|---|---|---|
| 1 | `find-skills` | ✅ 已安装 — 搜索和发现可用技能 |

## 🔧 常用命令

| 命令 | 说明 |
|---|---|
| `npx skills add <source>` | 安装技能 |
| `npx skills list` | 列出已安装技能 |
| `npx skills find [query]` | 搜索技能 |
| `npx skills remove <skill>` | 移除技能 |
| `npx skills update [skill]` | 更新技能 |
| `npx skills use <source>` | 使用临时技能（不安装） |
| `npx skills init [name]` | 创建新的 SKILL.md 模板 |

## 🎯 支持的来源格式

```bash
# GitHub 简写
npx skills add vercel-labs/agent-skills

# GitHub URL
npx skills add https://github.com/vercel-labs/agent-skills

# 直接指向某个技能
npx skills add https://github.com/owner/repo/tree/main/skills/skill-name

# GitLab
npx skills add https://gitlab.com/org/repo

# 本地路径
npx skills add ./my-local-skills
```

## 🎯 选项

| 选项 | 说明 |
|---|---|
| `-g, --global` | 安装到用户目录（全局） |
| `-a, --agent <agents>` | 指定目标 Agent |
| `-s, --skill <skills>` | 安装指定技能 |
| `-l, --list` | 列出可用技能 |
| `--all` | 安装所有技能到所有 Agent |
| `-y, --yes` | 跳过确认 |

## 📂 安装位置

| 范围 | 路径 |
|---|---|
| **项目级** | `./<agent>/skills/` |
| **全局** | `~/.<agent>/skills/` |
