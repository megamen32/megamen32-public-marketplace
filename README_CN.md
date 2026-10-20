# megamen32 公共市场

[English](README.md) · [Русский](README_RU.md) · 中文

[megamen32](https://github.com/megamen32) 的可移植 [Agent Plugins 1.0.0](https://agent-plugins.org/) 公共市场。各客户端索引只列出兼容的插件；MiniMax Code 从 UserIO 源仓库直接导入，不使用本市场索引。

## 项目

- [ask-human](https://github.com/megamen32/ask-human-plugin) — 当代理无法安全自行继续时，请求人工决策或缺失的非机密信息。
- [ask-secret](https://github.com/megamen32/ask-secret-plugin) — 通过一次性浏览器页面让用户输入机密，不将机密放入聊天记录。
- [agent-herder](https://github.com/megamen32/agent-herder) — 协调编程代理会话、消息、所有权说明与自动监督。
- [grepmesh-search](https://github.com/megamen32/grepmesh/tree/main/plugins/grepmesh-search) — 在未知路径和已配置远程范围内搜索，避免无控制扫描。
- [fast-agent-plugin](https://github.com/megamen32/fast-agent-plugin/tree/main/plugins/fast-agent-plugin) — 用于构建更快代理工作流的命令和可移植技能。
- [gsd](https://github.com/megamen32/gsd-agent-plugin) — 面向代理辅助开发的完整规划、执行、审查和项目管理流程。
- [learn-hermes](https://github.com/megamen32/learn-hermes) — 在代理任务之间保留有用经验并改进技能。
- [ouroboros-self-improve](https://github.com/megamen32/ouroboros-self-improve-plugin) — 经过审查的代理反思与自我改进流程。
- [universal-userio](https://github.com/megamen32/universal-userio/tree/main/plugins/universal-userio) — Gmail、Telegram、WhatsApp、SMS、Matrix 和其他 UserIO 渠道的 Agent Plugin 1.0 包。
- [swap](https://github.com/megamen32/swap-agent-plugin) — 管理 SpaceWeb DNS、通配符 DDNS 和 Certbot DNS-01 验证。
- [regro](https://github.com/megamen32/regro-agent-plugin) — 管理 REG.RU DNS、双链路 DDNS 和 Certbot DNS-01 验证。
- [focus-group](https://github.com/megamen32/focus-group) — 在发给真人前，用独立的合成受众画像测试信件、提案或页面。

## 安装

### Codex

```bash
codex plugin marketplace add megamen32/megamen32-public-marketplace --ref main
codex plugin list --marketplace megamen32-public --available
```

目录：[.agents/plugins/marketplace.json](.agents/plugins/marketplace.json)

### Claude Code

```bash
claude plugin marketplace add megamen32/megamen32-public-marketplace
claude plugin install gsd@megamen32-public-claude
```

目录：[.claude-plugin/marketplace.json](.claude-plugin/marketplace.json)

### MiniMax Code (UserIO)

MiniMax Code 不导入本市场索引。请从以下 GitHub 子目录导入 UserIO：
`https://github.com/megamen32/universal-userio/tree/main/plugins/universal-userio`。
[MiniMax Code 安装指南](https://github.com/megamen32/universal-userio/blob/main/docs/guide/minimax-code.md)

客户端需要不同格式的市场索引，因此此仓库保留了单独的客户端索引。MiniMax Code 直接导入 UserIO 插件子目录，不安装本市场索引。
