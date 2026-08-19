# Instalação detalhada

SEFAZ RJ: Certidão Negativa de Débitos (Certificado Digital) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_rj_certidao_debitos_cert`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_rj_certidao_debitos_cert` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_rj_certidao_debitos_cert` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_rj_certidao_debitos_cert` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_rj_certidao_debitos_cert` (ou `servers.sefaz_rj_certidao_debitos_cert` no VS Code) do config do cliente e reinicie.
