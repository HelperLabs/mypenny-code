# @mypenny/code-claude-code

Claude Code plugin shell for MyPenny memory. It bundles the Penny skill plus
hook config files; hook behavior lives in `@mypenny/code-core`.

## Install (once published)
```
/plugin install mypenny-code-claude-code@mypenny
```

## Upgrade

Refresh the `mypenny` marketplace/source, then reinstall
`mypenny-code-claude-code` from the plugin browser or rerun:

```
/plugin install mypenny-code-claude-code@mypenny
```

After upgrading, restart Claude Code or open a fresh session so the bundled
Penny skill and hooks reload.

## First-launch
On first SessionStart the plugin prints an auth hint to stderr with the exact
resolved path to the bundled login script, e.g.:
*"[mypenny] plugin not authenticated. Run: node \"<plugin-dir>/scripts/auth_login.mjs\""*

Run that command, sign in, approve in your browser, and re-open the session.
