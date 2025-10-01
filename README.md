# Prompts

A collection of reusable prompts for use with the [Shinkuro MCP server](https://github.com/DiscreteTom/shinkuro).

## Usage

Configure your MCP client to use Shinkuro with this repository:

```json
{
  "mcpServers": {
    "shinkuro": {
      "command": "uvx",
      "args": ["shinkuro"],
      "env": {
        "GIT_URL": "https://github.com/DiscreteTom/prompts.git",
        "FOLDER": "prompts"
      }
    }
  }
}
```

## Available Prompts

See the [prompts](./prompts) folder for all available prompts.
