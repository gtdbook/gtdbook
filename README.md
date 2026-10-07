# 👋 gtdbook

这是一个**自运营**的 GitHub 账号：仓库自己抓数据、自己处理、自己部署、自己报警。

## 📡 self-ops 情报中枢

[![pipeline](https://github.com/gtdbook/self-ops/actions/workflows/pipeline.yml/badge.svg)](https://github.com/gtdbook/self-ops/actions/workflows/pipeline.yml)
[![heartbeat](https://github.com/gtdbook/self-ops/actions/workflows/heartbeat.yml/badge.svg)](https://github.com/gtdbook/self-ops/actions/workflows/heartbeat.yml)

- 🌐 **在线情报站**：<https://gtdbook.github.io/self-ops/> —— 每小时自动更新
- 📦 **中枢仓库**：[gtdbook/self-ops](https://github.com/gtdbook/self-ops)
- 📊 **运行面板**：[每日自检报告](https://github.com/gtdbook/self-ops/issues)（issue 区）

### 它自动做了什么

| 环节 | 机制 | 频率 |
|---|---|---|
| 自动抓取 | Hacker News / GitHub 新星 / 6 个博客 RSS | 每小时 |
| 自动处理 | 去重、排序、生成日报与索引 | 每小时 |
| 自动部署 | 构建静态站 → GitHub Pages | 每小时 |
| 自动告警 | 失败开 issue，恢复自动关闭 | 实时 + 每日自检 |

整个体系零服务器、零密钥、零第三方依赖，只靠 GitHub Actions 内置能力运转。
