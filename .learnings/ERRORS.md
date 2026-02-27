## [ERR-20260227-001] exec_approval_timeout

**Logged**: 2026-02-27T05:12:00Z
**Priority**: low
**Status**: pending
**Area**: docs

### Summary
Command failed due to approval timeout while searching local OpenClaw docs.

### Error
```
Exec denied (approval-timeout): rg -n "discord" /root/.nvm/versions/node/v22.22.0/lib/node_modules/openclaw/docs
```

### Context
- Command/operation attempted: rg search in OpenClaw docs
- Input or parameters used: "discord" keyword
- Environment details: OpenClaw workspace in restricted approval mode

### Suggested Fix
Re-run with approval or avoid exec by using read to open docs directly.

### Metadata
- Reproducible: yes
- Related Files: /root/.nvm/versions/node/v22.22.0/lib/node_modules/openclaw/docs

---
