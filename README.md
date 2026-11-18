# VerbaDraw — releases

Public releases of the **VerbaDraw MCP server** and the **VerbaDraw extension for VS Code**.
The source code is private; this repository only holds release notes and files.

| Product | Get it | Releases |
|---|---|---|
| **MCP server** — lets AI apps (Claude, Cursor, VS Code) validate, edit and render Mermaid diagrams | [npm: `verbadraw-mcp`](https://www.npmjs.com/package/verbadraw-mcp) | tags `mcp-v*` |
| **VS Code extension** — Markdown with live, editable Mermaid diagrams | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=verbadraw.verbadraw-vscode) · search **VerbaDraw** in the Extensions view | tags `ext-v*` |
| **Desktop app** (Windows, Linux) | [Download page](https://verbadraw.vercel.app/download) | [verbadraw-desktop-releases](https://github.com/Muavia842/verbadraw-desktop-releases/releases) |

## MCP server — quick start

Needs Node.js 20.19+. In Claude Code:

```
claude mcp add verbadraw -- npx -y verbadraw-mcp@latest --root .
```

Other clients: see the latest [`mcp-v*` release](https://github.com/Muavia842/verbadraw-releases/releases).

## VS Code extension — quick start

Extensions view (Ctrl+Shift+X) → search **VerbaDraw** → Install. Then open a Markdown file →
**Reopen Editor With… → VerbaDraw**.
