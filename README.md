# megamen32 public marketplace

English · [Русский](README_RU.md) · [中文](README_CN.md)

Public marketplace of portable [Agent Plugins 1.0.0](https://agent-plugins.org/) by [megamen32](https://github.com/megamen32). Codex and Claude Code are equal clients of one public collection.

## Projects

- [ask-human](https://github.com/megamen32/ask-human-plugin) — request a human decision or missing non-secret information when an agent cannot safely proceed alone.
- [ask-secret](https://github.com/megamen32/ask-secret-plugin) — hand a secret-entry step to the user through a one-time browser page, without putting the secret in chat.
- [agent-herder](https://github.com/megamen32/agent-herder) — coordinate coding-agent sessions, messages, ownership notes, and autopilot supervision.
- [grepmesh-search](https://github.com/megamen32/grepmesh/tree/main/plugins/grepmesh-search) — search unknown paths and configured remote scopes without uncontrolled scanning.
- [fast-agent-plugin](https://github.com/megamen32/fast-agent-plugin/tree/main/plugins/fast-agent-plugin) — commands and portable skills for building faster agent workflows.
- [last-human-commit](https://github.com/megamen32/LastHumanCommit/tree/main/plugins/last-human-commit) — business-first engineering workflow: research, implementation, testing, and release.
- [gsd](https://github.com/megamen32/gsd-agent-plugin) — a complete planning, execution, review, and project-management workflow for agent-assisted development.
- [learn-hermes](https://github.com/megamen32/learn-hermes) — preserve useful lessons and improve skills across agent work instead of losing them after a task.
- [ouroboros-self-improve](https://github.com/megamen32/ouroboros-self-improve-plugin) — reviewed reflection and self-improvement workflow for agents.
- [universal-userio](https://github.com/megamen32/universal-userio) — one interface for Gmail, Telegram, WhatsApp, SMS, Matrix, and other user communications.
- [swap](https://github.com/megamen32/swap-agent-plugin) — operate SpaceWeb DNS, wildcard DDNS, and Certbot DNS-01 challenges.
- [regro](https://github.com/megamen32/regro-agent-plugin) — operate REG.RU DNS, dual-uplink DDNS, and Certbot DNS-01 challenges.
- [focus-group](https://github.com/megamen32/focus-group) — test a letter, offer, or page with independent synthetic recipient personas before sending it to people.

## Install

### Codex

```bash
codex plugin marketplace add megamen32/megamen32-public-marketplace --ref main
codex plugin list --marketplace megamen32-public --available
```

Catalog: [.agents/plugins/marketplace.json](.agents/plugins/marketplace.json)

### Claude Code

```bash
claude plugin marketplace add megamen32/megamen32-public-marketplace
claude plugin install gsd@megamen32-public-claude
```

Catalog: [.claude-plugin/marketplace.json](.claude-plugin/marketplace.json)

The clients require different marketplace-index schemas, so this repository carries two small client indexes for the same projects. The plugins themselves remain portable Agent Plugins; neither catalog is the primary format.
