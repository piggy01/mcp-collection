# OthmanAdi/planning-with-files — Manus 式文件规划

| 项目 | 内容 |
|---|---|
| 🏢 **仓库** | [github.com/OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) |
| ⭐ **Stars** | 22.9k |
| 🍴 **Forks** | 2k |
| 📋 **版本** | v2.43.0 |
| 📅 **收录日期** | 2026-06-08 |

## 📝 简介

实现 Manus 风格的持久化 Markdown 规划系统——Meta 以 20 亿美元收购 Manus 背后的工作流模式。

作者：Ahmad Othman Ammar Adi

## 🧩 核心思想

```
Context Window = RAM（易失，有限）
Filesystem    = Disk（持久，无限）
→ 所有重要信息写入磁盘
```

## 📋 三文件模式

| 文件 | 作用 |
|---|---|
| `task_plan.md` | 记录阶段和进度 |
| `findings.md` | 存储调研和发现 |
| `progress.md` | 会话日志和测试结果 |

## 🧩 已安装技能

| 技能名 | 说明 |
|---|---|
| `planning-with-files-zh` | 🇨🇳 中文版文件规划技能 |

## 🌐 多语言版本

| 语言 | 安装命令 |
|---|---|
| 🇬🇧 English | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files -g` |
| 🇨🇳 简体中文 | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files-zh -g` |
| 🇹🇼 繁體中文 | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files-zht -g` |
| 🇸🇦 العربية | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files-ar -g` |
| 🇩🇪 Deutsch | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files-de -g` |
| 🇪🇸 Español | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files-es -g` |

## 🚀 安装方式

```bash
# 快速安装（简体中文版）
npx skills add OthmanAdi/planning-with-files --skill planning-with-files-zh -g

# Claude Code 插件（含 /plan 命令）
/plugin marketplace add OthmanAdi/planning-with-files
/plugin install planning-with-files@planning-with-files
```

## 📊 基准测试

| 指标 | 有技能 | 无技能 |
|---|---|---|
| 通过率 (30 断言) | **96.7%** | 6.7% |
| 三文件模式遵循 | **5/5** | 0/5 |
| 盲测 A/B 胜率 | **3/3** | 0/3 |
| 平均评分 | **10/10** | 6.8/10 |
