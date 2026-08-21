> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use "offer" as the umbrella term for anything a merchant creates (volume discount, product bundle, frequently bought together, mix and match) — not "bundle" or "discount" generically, since not every offer type is a bundle or a discount.
- Use "widget" for the on-storefront embedded UI a customer sees/interacts with.
- Use "app embed" specifically for the Online Store → Themes → App embeds toggle that turns the widget on for a theme.
- Use "store" or "merchant" for the person using Eazify AOV, "customer" or "shopper" for the person buying on the storefront. Never "user" for either — it's ambiguous between the two.
- Plan names are exactly "Free" and "Lifetime" (capitalized, no "Pro"/"Premium" — those don't exist in this product).

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- This is merchant-facing product documentation. Don't document internal/admin tooling (support scripts, webhook internals, HMAC signing, database schema, deployment) — that belongs in internal engineering docs, not here.
- Don't state exact prices, revenue limits, or per-plan feature caps in prose — these change independently of docs and go stale quickly. Point readers to the in-app Pricing page instead (see `plans.mdx` for the pattern).
- Don't claim a specific click-path (exact button/menu wording) unless it's been verified against the live app — prefer describing the outcome and a reasonably safe general location (e.g. "from the Eazify AOV navigation") over guessing exact labels.
