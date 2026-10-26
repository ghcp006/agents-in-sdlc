---
slug: zh-cn/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** 将 GitHub Copilot 作为代理式编码助手带入终端。它可以探索代码库、生成代码、运行命令并连接外部工具，所有操作都通过命令行完成，无需切换到图形化编辑器即可保持工作流畅。

本工作坊将带你完成 Tailspin Toys 的连续开发流程：在 GitHub Codespaces 中准备项目，添加星级评分并合并第一个拉取请求 (PR)，然后使用指令、技能、MCP 工具、QA 智能体和 Agent Merge 实现筛选功能。最后探索斜杠命令，并回顾如何复用所学内容。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 准备项目和 Codespace |
| [1. 安装 Copilot CLI][ex1] | 安装 | 安装并验证 Copilot CLI，然后熟悉其基本用法 |
| [2. 添加星级评分][ex2] | 首次更改 | 显示现有评分并合并第一个 PR |
| [3. 智能体模式：Plan 和 Autopilot][ex3] | 智能体模式 | 根据议题规划功能，使用 Autopilot 实现，并在 Interactive 模式下审查 |
| [4. 使用自定义指令引导 Copilot][ex4] | 上下文 | 更新指令并将其应用于筛选功能 |
| [5. 自定义并使用 quality-checks 技能][ex5] | 可重复检查 | 更新技能的报告格式并运行项目检查 |
| [6. 使用 Playwright MCP 验证功能][ex6] | 浏览器观察 | 在 CLI 中配置 MCP 并检查筛选行为 |
| [7. 创建并使用 QA 智能体][ex7] | 需求与覆盖率 | 检查需求、覆盖率和验证证据 |
| [8. 创建并合并功能 PR][ex8] | 审查与合并 | 审查完整更改并使用 Agent Merge |
| [9. GitHub Copilot CLI 中的斜杠命令][ex9] | CLI 功能 | 探索上下文、模型、共享和可选委派 |
| [10. 总结与后续步骤][ex10] | 总结 | 回顾工作流、可复用的自定义配置和其他资源 |
| [可选：集成 Foundry][foundry] | 托管智能体 | 准备模型、部署基于目录的智能体并将其连接到网站 |

## 先决条件

参加本工作坊前，请确保已具备以下条件：

- [ ] 拥有 GitHub 账户，并已启用 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划
- [ ] 有权创建存储库和 Codespace
- [ ] 对终端或命令行操作有基本了解

> [!TIP]
> 没有付费计划？已验证学生可通过 [GitHub Education][callout-student-plan-education] 免费使用 GitHub Copilot。**Copilot Student** 计划包含本工作坊所用的智能体、MCP、代码审查和 Copilot CLI 功能，因此可以完整完成所有路径。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> 如果使用的是 Copilot Business 或 Copilot Enterprise，请确认管理员已启用 Copilot CLI。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
