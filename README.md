# pulse-signin

Sign-in (OAuth consent) page for the Manor Build "Pulse" connector in Claude, served by GitHub Pages at
https://manor-group-nz-ltd.github.io/pulse-signin/oauth/consent

- Supabase Auth (project pqktuashmnsqxehhyznu) sends staff here when they connect Pulse in claude.ai.
- They sign in with Microsoft 365, the page checks they are active Pulse office staff, and they press Allow or Deny.
- The page holds only the Supabase project URL and publishable key, which are public by design. No secrets belong in this repo.
- Design and build log: private repo Manor-Group-NZ-Ltd/pulse, docs/PULSE_CONNECTOR_DESIGN.md and docs/BUILD_LOG.md.
