# vaulted-logic-tools

Two static pages (home + privacy policy) served by GitHub Pages at https://afsarctg.github.io/vaulted-logic-tools/.

**Why it exists:** Google's OAuth consent screen for the GCP project `vaulted-logic-tools` needs a homepage and a privacy policy
URL on an authorized domain before the app can be set to "In production". In "Testing" status, refresh tokens expire after
7 days. The project is the operator's personal OAuth client for Claude Code tools (gws CLI, GA4 MCP, Search Console);
machine-wide guide: `~/.claude/references/google-services-access.md`.

**Branding settings (Google Auth Platform → Branding):** homepage `https://afsarctg.github.io/vaulted-logic-tools/`, privacy
`https://afsarctg.github.io/vaulted-logic-tools/privacy.html`, authorized domain `afsarctg.github.io`.

Created 2026-10-28 by Claude Code (growth-studio session) at the operator's request. Separate from the FARE site in
`afsarctg/afsarctg.github.io`; never edit that repo from here. No secrets in this repo, ever (the OAuth client JSON lives only in
`~/.config/gws/client_secret.json`).
