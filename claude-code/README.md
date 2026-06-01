# @mypenny/code-claude-code

Claude Code plugin shell for MyPenny memory. Hook config files only —
all behavior lives in `@mypenny/code-core`.

## Install (once published)
```
/plugin install mypenny-code-claude-code@mypenny
```

## First-launch
On first SessionStart the plugin will print to stderr:
*"MyPenny plugin not authenticated. Run: npx @mypenny/code-core auth login"*

Run that command, sign in, approve in your browser, and re-open the session.
