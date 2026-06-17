# Lumira documentation project

This is the Mintlify documentation site for Lumira.

## Framework

- Configuration lives in `docs.json`.
- Pages are MDX files with YAML frontmatter.
- Custom Lumira styling lives in `style.css`.
- Use `mint dev` to preview locally.
- Use `mint broken-links` to check navigation and links when the Mintlify CLI is available.

## Product terminology

- Use **workspace**, not project.
- Use **member** for people inside Discord/Roblox communities.
- Use **ranking account** for the Roblox account connected through OAuth.
- Use **Support PIN** for support verification. Do not tell users to send private credentials.
- Use **Core** and **Pro** for public plan language.

## Content rules

- Lumira v2 ranking uses Roblox OAuth. Do not document `.ROBLOSECURITY` setup as an accepted ranking method.
- Do not document internal-only staff portal implementation details.
- Do not publish secrets, tokens, API keys, bot tokens, cookies, client secrets, or database details.
- Support requests should go through Discord and include a Support PIN when requested.

## Writing style

- Use active voice and second person.
- Keep sentences short.
- Use sentence case for headings.
- Bold UI labels, for example: Click **Settings**.
- Use code formatting for commands, file paths, scopes, endpoints, and IDs.
