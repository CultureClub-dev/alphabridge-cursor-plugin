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

- `mcp.json`: the address of the hub, the free AlphaBridge service that links your sites to Cursor, `https://connect.alphabridge-mcp.com/mcp` (Streamable HTTP, OAuth 2.1).
- `skills/wordpress-with-alphabridge`: how the agent should work on a WordPress site (read first, one change at a time, undo).

## Editions

The free plugin offers 80 tools: posts, pages, media, terms, comments, menus, widgets, user accounts, SEO fields, site settings and maintenance, and in WooCommerce prices, stock, order status and coupons. Changes to the title, content, excerpt, status, slug, parent, author or date of a post or page, status changes in bulk and changes of the site settings can be undone for 7 days. Pro adds page-builder texts, search & replace, code with a safety net, installing and updating plugins and themes, and undo that also covers files and snippets, adjustable up to 30 days. See [alphabridge-mcp.com](https://alphabridge-mcp.com).

## License

MIT
