### Initialize

`ùv init`

### Create venv

`uv venv`
`.venv\Scripts\activate`

###

`uv add "mcp[cli]" `

### run with mcp inspector...

`uv run mcp dev servers/weather.py`

### run with cloude desktop

`uv run mcp install servers/weather.py`

- it is automatically added to the claude.

### this can do with cursor also

### cmd terminal also can be used.

### all mcp servers that we created are added to the file "claude_desktop_config.json"

### Add mcp client
```uv add mcp-use```

### To run
```uv run servers/client.py```

- did not run correctly

### to run correctly
```uv run mcpserver/server.py```