# Ultra MCP

An MCP server for the Ultra Profiler/Firefox .json trace format.

See the Ultra profiler project here:

https://github.com/xoofx/ultra

```
dotnet tool update -g ultramcp
```

Configure your MCP-aware client to launch it. For VS Code, add to .vscode/mcp.json:

```json
{
  "servers": {
    "ultramcp": {
      "type": "stdio",
      "command": "ultramcp"
    }
  }
}
```
