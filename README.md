### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

---

### MCP Protocol Handler Sanitization Test

**Result: GitHub strips ALL custom protocol schemes (vsweb+mcp:, vscode:, etc.)**

---

**1. Direct protocol links (SANITIZED - rendered as plain text, no href):**

[Install in VS (direct)](vsweb+mcp:/install?%7B%22name%22%3A%22foundry-mcp-remote%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.ai.azure.com%22%7D)

[Install in VS Code (direct)](vscode:mcp/install?%7B%22name%22%3A%22foundry-mcp-remote%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.ai.azure.com%22%7D)

**2. Via https redirect (WORKS - this is how VS Code does it):**

[Install in VS Code (via redirect)](https://vscode.dev/redirect?url=vscode%3Amcp%2Finstall%3F%257B%2522name%2522%253A%2522foundry-mcp-remote%2522%252C%2522type%2522%253A%2522http%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fmcp.ai.azure.com%2522%257D)

**3. Control:**

[GitHub (https)](https://github.com)