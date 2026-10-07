# 👋 gtdbook

这是一个**自运营、自进化**的 GitHub 账号：仓库自己抓数据、自己处理、自己部署、自己报警，还根据投票学习你的口味。

## 📡 self-ops 情报中枢

[![pipeline](https://github.com/gtdbook/self-ops/actions/workflows/pipeline.yml/badge.svg)](https://github.com/gtdbook/self-ops/actions/workflows/pipeline.yml)
[![heartbeat](https://github.com/gtdbook/self-ops/actions/workflows/heartbeat.yml/badge.svg)](https://github.com/gtdbook/self-ops/actions/workflows/heartbeat.yml)
[![evolve](https://github.com/gtdbook/self-ops/actions/workflows/evolve.yml/badge.svg)](https://github.com/gtdbook/self-ops/actions/workflows/evolve.yml)

- 🌐 **在线情报站**：<https://gtdbook.github.io/self-ops/> —— 每小时自动更新，含 [RSS 订阅](https://gtdbook.github.io/self-ops/feed.xml)
- 📦 **中枢仓库**：[gtdbook/self-ops](https://github.com/gtdbook/self-ops)
- 📊 **运行面板**：[每日自检报告](https://github.com/gtdbook/self-ops/issues)（issue 区）
- 📰 **每日情报 issue**：每天早晨自动发布，回复 like/dislike 即可训练体系口味

### 它自动做了什么

| 环节 | 机制 | 频率 |
|---|---|---|
| 自动抓取 | Hacker News / GitHub 新星 / Product Hunt / 6 个博客 RSS | 每小时 |
| 自动处理 | 去重、多源共振聚类、飙升榜、生成日报与索引 | 每小时 |
| 自动部署 | 构建静态站 + RSS → GitHub Pages | 每小时 |
| 自动告警 | 失败开 issue，恢复自动关闭 | 实时 + 每日自检 |
| 自我进化 | 日报 issue 口味投票 → 板块权重与关键词权重学习 | 每日 |

整个体系零服务器、零密钥、零第三方依赖，只靠 GitHub Actions 内置能力运转。
