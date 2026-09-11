# megamen32 public Agent Plugins marketplace

Public, Codex-first marketplace for portable [Agent Plugins 1.0.0](https://agent-plugins.org/) packages maintained by `megamen32`.

## Primary format: OpenAI Codex / Agent Plugins

The canonical marketplace is:

```text
.agents/plugins/marketplace.json
```

It references each public plugin's `main` branch without a SHA pin, so GitHub marketplace sync / Codex marketplace upgrade can receive future validated plugin updates.

Add it to Codex:

```bash
codex plugin marketplace add megamen32/megamen32-public-marketplace --ref main
codex plugin list --marketplace megamen32-public --available
codex plugin add agent-herder@megamen32-public
```

Every plugin in the Codex catalog has a root `plugin.json` conforming to Agent Plugins 1.0.0.

## Claude compatibility mirror

`.claude-plugin/marketplace.json` is only a compatibility mirror and intentionally lists **only plugins that actually ship a Claude plugin manifest**. Portable Agent Plugins are not advertised as Claude plugins merely because they share skills.

## Catalog

The manifests are the source of truth for what is published here: the Codex/Agent Plugins catalog currently carries `ask-human`, `ask-secret`, `agent-herder`, `grepmesh-search`, `fast-agent-plugin`, `last-human-commit`, `learn-hermes`, `ouroboros-self-improve`, `universal-userio`, `swap` (SpaceWeb DNS toolkit) and `regro` (REG.RU DNS toolkit). Policy: **everything public lives here**; the private `megamen32-marketplace` holds only what is not in this catalog.

## Private catalog

Internal/private plugins remain separate in the private `megamen32-marketplace` repository and are never mirrored here.
