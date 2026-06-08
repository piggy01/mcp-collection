# obra/superpowers — Agent 开发工作流框架

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [github.com/obra/superpowers](https://github.com/obra/superpowers) |
| ⭐ **Stars** | 221k |
| 🍴 **Forks** | 19.7k |
| 📋 **技能数** | 14 个 |
| 📅 **收录日期** | 2026-06-08 |

## 📝 简介

Superpowers 是一套完整的 AI Agent 软件开发方法论，构建在一组可组合的技能之上。从需求澄清→设计→计划→实现→审查→合并，形成完整闭环。

作者：Jesse Vincent（Prime Radiant）

## 🧩 技能清单

| # | 技能名 | 工作流阶段 | 说明 |
|---|---|---|---|
| 1 | `brainstorming` | 🧠 需求 | Socratic 式设计细化，发散思考 |
| 2 | `writing-plans` | 📋 规划 | 将设计拆分为可执行的实施计划 |
| 3 | `using-git-worktrees` | 🔧 环境 | 创建隔离的 Git 工作目录 |
| 4 | `test-driven-development` | 🧪 实现 | RED-GREEN-REFACTOR TDD 循环 |
| 5 | `subagent-driven-development` | 🤖 实现 | 子代理分发任务 + 两阶段审查 |
| 6 | `executing-plans` | 📋 执行 | 分批执行计划，含人工检查点 |
| 7 | `dispatching-parallel-agents` | 🤖 并行 | 并行执行无依赖的独立任务 |
| 8 | `requesting-code-review` | 🔍 审查 | 提交前的自检和审查请求 |
| 9 | `receiving-code-review` | 🔍 审查 | 收到审查反馈后的处理流程 |
| 10 | `finishing-a-development-branch` | 🏁 收尾 | 功能完成后的分支合并决策 |
| 11 | `systematic-debugging` | 🐛 调试 | 4 阶段根因分析调试法 |
| 12 | `verification-before-completion` | ✅ 验证 | 完成前的自动化验证检查 |
| 13 | `using-superpowers` | 📖 指南 | Superpowers 系统的使用说明 |
| 14 | `writing-skills` | ✍️ 元技能 | 创建新技能的最佳实践 |

## 🔄 默认工作流

```
brainstorming → writing-plans → subagent-driven-development
     ↓               ↓                    ↓
  设计文档         实施计划          两阶段审查
                                       ↓
                              requesting-code-review
                                       ↓
                              finishing-a-development-branch
```

## 🚀 安装方式

### Claude Code（官方插件市场）
```
/plugin install superpowers@claude-plugins-official
```

### Codex CLI
```
/plugins → 搜索 Superpowers → Install
```

### Gemini CLI
```
gemini extensions install https://github.com/obra/superpowers
```

### Cursor
```
/add-plugin superpowers
```
