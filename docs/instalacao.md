# Instalação detalhada

CPFL: Download via link é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_contas_cpfl_link`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_contas_cpfl_link` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_contas_cpfl_link` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_contas_cpfl_link` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.contas_cpfl_link` (ou `servers.contas_cpfl_link` no VS Code) do config do cliente e reinicie.
