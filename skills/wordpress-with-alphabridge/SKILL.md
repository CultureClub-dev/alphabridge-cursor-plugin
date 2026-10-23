---
name: wordpress-with-alphabridge
description: Work on a self-hosted WordPress site through the AlphaBridge MCP server. Use when the user asks to read, write or fix content, SEO, media or WooCommerce data on their WordPress site.
---

# WordPress with AlphaBridge

## When to use

- The user names one of their WordPress sites or asks about posts, pages, media, comments, SEO titles or products.
- The AlphaBridge MCP server is connected (it shows up as `alphabridge`).

## Instructions

1. Every tool call needs a `site` argument. Call `connect_status` first if you do not know which sites are connected. New sites are added with `connect_add_site`.
2. Read before you write. List or fetch what you are about to change, and tell the user what you found.
3. A new connection is read-only. If a write tool is refused, tell the user that an administrator can switch on write access in WordPress under Settings → AlphaBridge MCP. Do not look for a way around it.
4. Change one thing at a time and report what changed, with the post or product ID.
5. On sites with AlphaBridge Pro, every change can be undone: `wp_undo_list` shows recent changes, `wp_undo` reverts one.
6. Never ask the user for WordPress passwords or tokens. Sign-in happens in the browser when Cursor shows "Authenticate".
