# Add TokRepo — open registry for AI skills, prompts, and MCP configs

Resolves #1384

## Submission

- **Name**: TokRepo
- **Website**: https://tokrepo.com
- **Author**: William Wang
- **GitHub**: https://github.com/henu-wang

## Description

TokRepo is an open registry of 200+ curated AI assets — skills, prompts, MCP configs, and workflows. Includes a CLI (`npx tokrepo search`) and an MCP server (`npx tokrepo-mcp-server`) so Claude Code can search and install assets mid-conversation. No signup needed, zero dependencies.

## Suggested Section

Agent Skills > General

## Key Features

- **CLI**: `npx tokrepo search "code review"` — zero-install search
- **MCP Server**: `claude mcp add tokrepo -- npx tokrepo-mcp-server` — 4 tools for search, trending, detail, install
- **200+ curated assets**: Skills, prompts, MCP configs, workflows
- **Zero dependencies**: Single-file CLI and MCP server for fast startup

## Suggested Entry

```markdown
- [TokRepo](https://tokrepo.com) by [William Wang](https://github.com/henu-wang) - An open registry of 200+ curated AI assets — skills, prompts, MCP configs, and workflows. Includes a CLI (`npx tokrepo search`) and an MCP server (`npx tokrepo-mcp-server`) so Claude Code can search and install assets mid-conversation. No signup needed, zero dependencies.
```

## How to Install / Use with Claude Code

### 1. Use the CLI (zero install)

```bash
npx tokrepo search "code review"
```

### 2. Add the MCP Server to Claude Code

```bash
claude mcp add tokrepo -- npx tokrepo-mcp-server
```

This adds 4 tools to Claude Code:
- `search` – search the registry by keyword
- `trending` – browse trending assets
- `detail` – get full details of a specific asset
- `install` – install an asset directly into your project

### 3. Use mid-conversation

Once the MCP server is added, you can ask Claude Code:
- "Search TokRepo for a code review skill"
- "Show me trending prompts on TokRepo"
- "Install the best Python testing workflow from TokRepo"

## Checklist

- [x] I have read the [Contributing Guidelines](CONTRIBUTING.md)
- [x] The resource is relevant to Claude Code users
- [x] The resource is actively maintained
- [x] The description is accurate and concise
