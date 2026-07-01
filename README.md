# Ultra MCP

An MCP server for the Ultra Profiler/Firefox .json trace format.

https://github.com/xoofx/ultra

```
dotnet tool update -g ultramcp
```

Configure your MCP-aware client to launch it. For VS Code, add to .vscode/mcp.json:

{
  "servers": {
    "ultramcp": {
      "type": "stdio",
      "command": "ultramcp"
    }
  }
}