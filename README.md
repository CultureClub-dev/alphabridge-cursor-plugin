# AlphaBridge MCP for WordPress: Cursor plugin

Run all of WordPress from Cursor: SEO, security, your WooCommerce shop and Elementor pages, on up to 10 websites in one connection. Powered by [AlphaBridge](https://alphabridge-mcp.com). Start free.

## What you need

- The free [AlphaBridge MCP plugin](https://wordpress.org/plugins/alphabridge-mcp/) on each WordPress site (WordPress 6.5+, PHP 8.0+).
- An administrator login on each site.

## Setup

1. Install this plugin from the Cursor Marketplace.
2. In Cursor, open the MCP settings and click **Authenticate** next to `alphabridge`.
3. Enter your site, sign in to WordPress and approve the connection. Up to 10 sites can share one connection.

The connection starts read-only. An administrator switches on write access in WordPress under Settings → AlphaBridge MCP.

## What is inside

- `mcp.json`: the AlphaBridge Connect endpoint `https://connect.alphabridge-mcp.com/mcp` (Streamable HTTP, OAuth 2.1).
- `skills/wordpress-with-alphabridge`: how the agent should work on a WordPress site (read first, one change at a time, undo with Pro).

## Editions

The free plugin offers 40 tools: posts, pages, media, terms, comments and widgets, and it reads SEO fields. Pro adds WooCommerce, SEO writing, menus, users and undo for every change. See [alphabridge-mcp.com](https://alphabridge-mcp.com).

## License

MIT
