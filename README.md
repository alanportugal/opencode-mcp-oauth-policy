# OpenCode MCP OAuth policy pages

Static public pages backing the OAuth consent screen for a personal, single-user OpenCode
integration (Gmail + Google Calendar MCP servers running locally).

- `index.html` — what the application is and is not
- `privacy.html` — what is accessed, where it goes, how to revoke

No JavaScript, no external assets, no analytics. Two files, served as-is by GitHub Pages.

## Why it is a separate repo

The runbook repo (`opencode_restore`) is private. These pages exist to be linked from a public
OAuth consent screen, so they live in their own public repo and nothing else does.
