# megamen32 public marketplace

Public marketplace of portable [Agent Plugins 1.0.0](https://agent-plugins.org/) by [megamen32](https://github.com/megamen32). Codex and Claude Code are first-class clients of the same public collection.

## Projects

- [ask-human](https://github.com/megamen32/ask-human-plugin)
- [ask-secret](https://github.com/megamen32/ask-secret-plugin)
- [agent-herder](https://github.com/megamen32/agent-herder)
- [grepmesh-search](https://github.com/megamen32/grepmesh/tree/main/plugins/grepmesh-search)
- [fast-agent-plugin](https://github.com/megamen32/fast-agent-plugin/tree/main/plugins/fast-agent-plugin)
- [last-human-commit](https://github.com/megamen32/LastHumanCommit/tree/main/plugins/last-human-commit)
- [gsd](https://github.com/megamen32/gsd-agent-plugin)
- [learn-hermes](https://github.com/megamen32/learn-hermes)
- [ouroboros-self-improve](https://github.com/megamen32/ouroboros-self-improve-plugin)
- [universal-userio](https://github.com/megamen32/universal-userio)
- [swap](https://github.com/megamen32/swap-agent-plugin)
- [regro](https://github.com/megamen32/regro-agent-plugin)
- [focus-group](https://github.com/megamen32/focus-group)

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

The two catalogs expose the plugin manifests supported by their respective clients; neither is presented as the primary format.
