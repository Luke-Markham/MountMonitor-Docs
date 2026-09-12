# Documentation project instructions

## About this project

- This is the shop-facing Help Center for [MountMonitor](https://www.mountmonitor.com), built on [Mintlify](https://mintlify.com)
- Audience is taxidermy shop owners and staff, not engineers or MountMonitor admins
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use **shop** for the taxidermy business using MountMonitor
- Use **client**, not customer, when referring to the shop's hunter or customer record
- Use **job** for a piece of work, not order
- Use **booking** for the public intake form at `/book/[slug]`. Do not call this the Client Portal
- Use **Client Portal** for `portal.mountmonitor.com`, where existing clients check jobs and can pay later
- Use **deposit** for the calculated amount stored on a job. Clients are not charged on the public booking form today
- Use **pending** for bookings that still need staff review on the jobs board
- Use **MountMonitor Payments** / Stripe when card charging is connected. Cash and check can still be recorded on the job

## Style preferences

- English only. Do not use Māori words or greetings
- Never use em dashes. Use periods, commas, parentheses, or separate sentences
- Use active voice and second person ("you")
- Keep sentences concise. One idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document shop-facing product only
- Do not document `/admin`, the Hetzner agent, internal Firestore, or other internal systems
- Do not document unreleased features as shipped. Pay-at-booking is not live
- Do not invent SMS plan limits. Website and product can disagree
- Stay high-level on UI paths when the exact click path is unclear
- Support contact: [contact@mountmonitor.com](mailto:contact@mountmonitor.com)
- Shop app: [https://app.mountmonitor.com](https://app.mountmonitor.com)
