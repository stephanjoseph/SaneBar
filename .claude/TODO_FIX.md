
## claude-mem Plugin Broken (2026-01-12)

Stop hooks failing with MODULE_NOT_FOUND:
- `/Users/sj/.claude/plugins/cache/thedotmack/claude-mem/8.5.9/scripts/worker-service.cjs`
- `/Users/sj/.claude/plugins/cache/thedotmack/claude-mem/8.5.9/scripts/summary-hook.js`

**Fix**: Reinstall or update the claude-mem plugin:
```bash
# Check plugin status
ls -la ~/.claude/plugins/cache/thedotmack/claude-mem/

# Reinstall
claude plugins uninstall thedotmack/claude-mem
claude plugins install thedotmack/claude-mem
```
