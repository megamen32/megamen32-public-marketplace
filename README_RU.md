# Публичный маркетплейс megamen32

[English](README.md) · Русский · [中文](README_CN.md)

Публичный маркетплейс переносимых [Agent Plugins 1.0.0](https://agent-plugins.org/) от [megamen32](https://github.com/megamen32). UserIO указан в каталоге проектов и индексе Codex. MiniMax Code импортирует его напрямую из исходного репозитория; в каталоге Claude Code UserIO пока не представлен.

## Проекты

- [ask-human](https://github.com/megamen32/ask-human-plugin) — запрашивает решение человека или недостающую несекретную информацию, когда агент не может безопасно продолжить сам.
- [ask-secret](https://github.com/megamen32/ask-secret-plugin) — передаёт ввод секрета пользователю через одноразовую страницу в браузере, не помещая секрет в чат.
- [agent-herder](https://github.com/megamen32/agent-herder) — координирует сессии агентов-разработчиков, сообщения, заметки о владении и автопилот.
- [grepmesh-search](https://github.com/megamen32/grepmesh/tree/main/plugins/grepmesh-search) — ищет в неизвестных путях и настроенных удалённых областях без неконтролируемого сканирования.
- [fast-agent-plugin](https://github.com/megamen32/fast-agent-plugin/tree/main/plugins/fast-agent-plugin) — команды и переносимые навыки для более быстрых агентных процессов.
- [gsd](https://github.com/megamen32/gsd-agent-plugin) — полный процесс планирования, выполнения, ревью и управления проектом для разработки с агентами.
- [learn-hermes](https://github.com/megamen32/learn-hermes) — сохраняет полезные выводы и улучшает навыки агента между задачами.
- [ouroboros-self-improve](https://github.com/megamen32/ouroboros-self-improve-plugin) — проверяемый процесс рефлексии и самоулучшения агентов.
- [universal-userio](https://github.com/megamen32/universal-userio/tree/main/plugins/universal-userio) — переносимый пакет Agent Plugin 1.0 для Gmail, Telegram, WhatsApp, SMS, Matrix и других каналов UserIO.
- [swap](https://github.com/megamen32/swap-agent-plugin) — управляет DNS SpaceWeb, wildcard DDNS и DNS-01-проверками Certbot.
- [regro](https://github.com/megamen32/regro-agent-plugin) — управляет DNS REG.RU, DDNS для двух uplink-каналов и DNS-01-проверками Certbot.
- [focus-group](https://github.com/megamen32/focus-group) — проверяет письмо, предложение или страницу на независимых синтетических портретах получателей до отправки людям.

## Установка

### Codex

```bash
codex plugin marketplace add megamen32/megamen32-public-marketplace --ref main
codex plugin list --marketplace megamen32-public --available
```

Каталог: [.agents/plugins/marketplace.json](.agents/plugins/marketplace.json)

### Claude Code

```bash
claude plugin marketplace add megamen32/megamen32-public-marketplace
claude plugin install gsd@megamen32-public-claude
```

Каталог: [.claude-plugin/marketplace.json](.claude-plugin/marketplace.json)

### MiniMax Code (UserIO)

MiniMax Code не импортирует индекс этого маркетплейса. Импортируйте UserIO как
отдельный GitHub-плагин из `https://github.com/megamen32/universal-userio/tree/main/plugins/universal-userio` либо
воспользуйтесь [руководством по MiniMax Code](https://github.com/megamen32/universal-userio/blob/main/docs/guide/minimax-code.md).

Клиентам нужны индексы маркетплейса с разными схемами, поэтому здесь есть отдельные индексы. MiniMax Code импортирует UserIO напрямую из каталога пакета и не устанавливает индекс этого маркетплейса.
