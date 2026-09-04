# Fibery

Fibery MCP server packaged as a Cursor plugin.

Connects to [Fibery](https://fibery.com) via the official remote MCP (`https://mcp.fibery.io/mcp`). Skills for common workflows are provided by the server after OAuth.

**Repo:** https://github.com/Fibery-inc/fibery-cursor-plugin

## Install

1. Install this plugin from the Cursor Marketplace (or load it locally while developing).
2. Complete Fibery OAuth when prompted — pick the workspace you want the agent to use.
3. Ask the agent to query schema, find entities, or update records in Fibery.

## MCP

| Server | Transport | URL |
| --- | --- | --- |
| `fibery` | streamable-http | `https://mcp.fibery.io/mcp` |

No API tokens in the plugin. Auth is OAuth against Fibery.

## Local development

```bash
cp -R . ~/.cursor/plugins/local/fibery
```

Then reload Cursor / enable local plugin imports if your org requires it.

## Docs

- [Connecting to Fibery MCP](https://developers.fibery.com/guides/mcp/connecting)
- [Fibery MCP overview](https://developers.fibery.com/guides/mcp/overview)
