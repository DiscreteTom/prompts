# Prompts

A collection of reusable prompts for use with the [Shinkuro MCP server](https://github.com/DiscreteTom/shinkuro-rs).

## Usage

Configure your MCP client to use Shinkuro with this repository:

[![Install MCP Server](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/cn/install-mcp?name=shinkuro&config=eyJlbnYiOnsiR0lUX1VSTCI6ImdpdEBnaXRodWIuY29tOkRpc2NyZXRlVG9tL3Byb21wdHMuZ2l0IiwiRk9MREVSIjoicHJvbXB0cyJ9LCJjb21tYW5kIjoibnB4IC15IHNoaW5rdXJvIn0%3D)
[![Add to Kiro](https://kiro.dev/images/add-to-kiro.svg)](https://kiro.dev/launch/mcp/add?name=shinkuro&config=%7B%22command%22%3A%22npx%22%2C%22args%22%3A%5B%22-y%22%2C%22shinkuro%22%5D%2C%22env%22%3A%7B%22GIT_URL%22%3A%22git%40github.com%3ADiscreteTom%2Fprompts.git%22%2C%22FOLDER%22%3A%22prompts%22%7D%7D)

```json
{
  "mcpServers": {
    "shinkuro": {
      "command": "npx",
      "args": ["-y", "shinkuro"],
      "env": {
        "GIT_URL": "git@github.com:DiscreteTom/prompts.git",
        "FOLDER": "prompts"
      }
    }
  }
}
```

## Available Prompts

See the [prompts](./prompts) folder for all available prompts.
