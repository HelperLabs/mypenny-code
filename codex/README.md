# @mypenny/code-codex

Codex plugin shell for MyPenny memory. Hook config only — behavior lives
in `@mypenny/code-core`. Codex's plugin shape (hooks.json schema,
`PLUGIN_ROOT` env var) deliberately matches Claude Code's, so the script
references are identical aside from the manifest format.

## Install (once published)
```
codex plugin marketplace add HelperLabs/mypenny-code
```
