# VaultCord MCP server

VaultCord connects your AI assistant to your [VaultCord](https://vaultcord.com) account so it can
manage your protected Discord servers: servers and settings, verification, members,
allow/block lists, backups and restores, custom bots, and orders.

- **Server:** `https://ai.vaultcord.com/mcp` (Streamable HTTP)
- **Auth:** OAuth 2.0 with dynamic client registration. No API key or client ID needed. You sign
  in to VaultCord the first time a tool is used.
- **Permissions:** every call runs with your own VaultCord permissions.
- **Docs:** https://docs.vaultcord.com · **Privacy:** https://vaultcord.com/privacy-policy · **Terms:** https://vaultcord.com/terms-of-service · **Support:** abuse@vaultcord.com

## One-click install

[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_VaultCord-0098FF?logo=visualstudiocode)](https://vscode.dev/redirect/mcp/install?name=vaultcord&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A//ai.vaultcord.com/mcp%22%7D)
[![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install_VaultCord-24bfa5?logo=visualstudiocode)](https://insiders.vscode.dev/redirect/mcp/install?name=vaultcord&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A//ai.vaultcord.com/mcp%22%7D&quality=insiders)

Or from a terminal:
```bash
code --add-mcp '{"name":"vaultcord","type":"http","url":"https://ai.vaultcord.com/mcp"}'
```
Then open Copilot Chat in **Agent mode** and sign in when prompted.

<!-- mcp-name: com.vaultcord/vaultcord -->
