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

## Plugin Patterns

- [docs/plugin-patterns.md](docs/plugin-patterns.md) — self-installing MCP servers, dependency management, orchestration in plugins
- [docs/mcp-framework.md](docs/mcp-framework.md) — which MCP Python framework we use and why
- [docs/mcp-proxy.md](docs/mcp-proxy.md) — whether MCP tool proxying/orchestration is appropriate, with authoritative sources

## Prerequisites

Each plugin may have its own prerequisites (e.g., `pipx install` for MCP server binaries). See the plugin's README for details.
