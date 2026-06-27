# @mypenny/code-codex

Codex plugin shell for MyPenny memory. It installs the MyPenny MCP server
definition and lifecycle hooks; hook behavior lives in `@mypenny/code-core`.
Codex exposes the installed plugin directory through `CODEX_PLUGIN_ROOT`.

## Install (once published)
```
codex plugin marketplace add HelperLabs/mypenny-code
codex plugin install mypenny-code-codex
```
