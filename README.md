<div align="center">

# ⚡ Studio MCP — Extended Edition

### Release channel — pre-built plugin only

[![Release](https://img.shields.io/github/v/release/6xvl/robloxstudio-mcp?style=for-the-badge&color=5865F2&label=Latest)](https://github.com/6xvl/robloxstudio-mcp/releases/latest)
[![npm](https://img.shields.io/npm/v/@6xvl/robloxstudio-mcp?style=for-the-badge&color=cb3837&label=npm)](https://www.npmjs.com/package/@6xvl/robloxstudio-mcp)
[![Downloads](https://img.shields.io/github/downloads/6xvl/robloxstudio-mcp/total?style=for-the-badge&color=a78bfa&label=Downloads&cacheSeconds=60)](https://github.com/6xvl/robloxstudio-mcp/releases)

> This repository is the **public release channel** for the plugin.
> It contains **only** the compiled, obfuscated `MCPPlugin-release.rbxmx` attached to each release tag.
> The plugin source is **private**.

---

</div>

## Install

### 1 · Plugin

Download [`MCPPlugin-release.rbxmx`](https://github.com/6xvl/robloxstudio-mcp/releases/latest) and drop into:

```
%LOCALAPPDATA%\Roblox\Plugins\
```

Restart Studio. Enable **Allow HTTP Requests** under Game Settings → Security.

### 2 · MCP server

| AI Tool | Command |
|---------|---------|
| **Claude Code** | `claude mcp add robloxstudio -- npx -y @6xvl/robloxstudio-mcp@latest` |
| **Codex CLI** | `codex mcp add robloxstudio -- npx -y @6xvl/robloxstudio-mcp@latest` |
| **Gemini CLI** | `gemini mcp add robloxstudio npx --trust -- -y @6xvl/robloxstudio-mcp@latest` |

Read-only inspector:

```
claude mcp add robloxstudio-inspector -- npx -y @6xvl/robloxstudio-mcp-inspector@latest
```

<details>
<summary><b>JSON-config clients (Claude Desktop, Cursor, Windsurf, etc.)</b></summary>

```json
{
  "mcpServers": {
    "robloxstudio": {
      "command": "npx",
      "args": ["-y", "@6xvl/robloxstudio-mcp@latest"]
    }
  }
}
```

</details>

---

## What this plugin does

96+ tools across scripts, instances, terrain, lighting, animation, sound, particles, tweens, materials, profiling, multi-Studio routing, and the Roblox official `StudioMCP.exe` hook (`rblx_*` tools).

See the [latest release notes](https://github.com/6xvl/robloxstudio-mcp/releases/latest) for the full tool list and changelog.

---

<div align="center">
<sub>Built for Studio. Powered by MCP.</sub>
</div>
