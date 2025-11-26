Install this MCP server by adding the following JSON code in your JSON config file 
```json
{
  "mcpServers": {
    "chess": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/pks1116/chess-mcp-server.git ",
        "chess"
      ]
    }
  }
}
```