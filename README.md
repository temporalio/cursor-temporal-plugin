# Temporal Developer Plugin for Cursor

This repository provides a [Cursor plugin](https://cursor.com/docs/plugins) for developing [Temporal](https://temporal.io/) applications.

> [!WARNING]
> This plugin is in Public Preview, and will continue to evolve and improve.
> We would love to hear your feedback - positive or negative - over in the [Community Slack](https://t.mp/slack), in the [#topic-ai channel](https://temporalio.slack.com/archives/C0818FQPYKY)

## Installation

This plugin is not yet available in the Cursor marketplace. To install it locally:

1. Clone this repository
2. Copy it into your Cursor local plugins directory:
   ```bash
   cp -r cursor-temporal-plugin ~/.cursor/plugins/local/temporal-developer
   ```
3. Restart Cursor
4. Navigate to **Settings → Plugins** and verify the plugin is listed

## What's Included

- **temporal-developer** skill — Comprehensive guidance for developing Temporal applications: creating workflows, activities, and workers; handling signals, queries, and updates; debugging non-determinism errors; implementing saga patterns, versioning strategies, and testing approaches across Python, TypeScript, Go, and Java SDKs.

## Standalone Skill

The skill content is derived from [temporalio/skill-temporal-developer](https://github.com/temporalio/skill-temporal-developer). If you only need the skill without the plugin wrapper, you can install it directly from that repo.

## Other Coding Agents

- **Claude Code**: See [temporalio/claude-temporal-plugin](https://github.com/temporalio/claude-temporal-plugin)
- **OpenAI Codex**: See [temporalio/codex-temporal-plugin](https://github.com/temporalio/codex-temporal-plugin)

## License

MIT
