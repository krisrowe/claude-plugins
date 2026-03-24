# Claude Plugins

Personal Claude Code plugin marketplace.

## Installation

```bash
claude plugin marketplace add krisrowe/claude-plugins
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [bills](https://github.com/krisrowe/bills-agent) | Bill tracking with Monarch recurring cross-reference | `claude plugin install bills@productivity` |
| [gapp](https://github.com/krisrowe/gapp) | Deploy Python MCP servers to Cloud Run with guided lifecycle, CI/CD, and user management | `claude plugin install gapp@productivity` |
| [plugin-creator](https://github.com/krisrowe/claude-plugin-creator) | Scaffold plugins with self-installing local MCP servers | `claude plugin install plugin-creator@productivity` |

## Plugin Architecture Docs

Architecture docs for building plugins with local MCP servers live in the [plugin-creator repo](https://github.com/krisrowe/claude-plugin-creator):

- [plugin-patterns.md](https://github.com/krisrowe/claude-plugin-creator/blob/main/docs/plugin-patterns.md) — self-installing MCP servers, dependency management, orchestration
- [mcp-framework.md](https://github.com/krisrowe/claude-plugin-creator/blob/main/docs/mcp-framework.md) — which MCP Python framework we use and why
- [mcp-proxy.md](https://github.com/krisrowe/claude-plugin-creator/blob/main/docs/mcp-proxy.md) — whether MCP tool proxying/orchestration is appropriate, with authoritative sources

## Prerequisites

Each plugin may have its own prerequisites (e.g., `pipx install` for MCP server binaries). See the plugin's README for details.
