# calendarmcp

FastAPI host for the MCP quickstart example.

## Run

```bash
uv run uvicorn main:app --reload
```

The FastAPI server starts on `http://127.0.0.1:8000`.

- MCP endpoint: `http://127.0.0.1:8000/mcp`
- FastAPI docs: `http://127.0.0.1:8000/docs`

## Included MCP features

- Tool: `add(a, b)`
- Resource: `greeting://{name}`
- Prompt: `greet_user(name, style="friendly")`
