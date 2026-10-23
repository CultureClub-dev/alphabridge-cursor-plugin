---
name: wordpress-with-alphabridge
description: Work on a self-hosted WordPress site through the AlphaBridge MCP server. Use when the user asks to read, write or fix content, SEO, media or WooCommerce data on their WordPress site.
---

# WordPress with AlphaBridge

## When to use

- The user names one of their WordPress sites or asks about posts, pages, media, comments, SEO titles or products.
- The AlphaBridge MCP server is connected (it shows up as `alphabridge`).

## Instructions

1. With several sites connected, every tool call needs a `site` argument naming one of them; with one site there is none. Call `connect_status` first if you do not know which sites are connected. New sites are added with `connect_add_site`.
2. Read before you write. List or fetch what you are about to change, and tell the user what you found.
3. A new connection is read-only. If a write tool is refused, tell the user that an administrator can switch on write access in WordPress under Settings → AlphaBridge MCP. Do not look for a way around it.
4. Change one thing at a time and report what changed, with the post or product ID.
5. On sites with AlphaBridge Pro, the changes that matter most can be undone with one call: posts and pages, page-builder elements, settings, theme switches, plugin and theme files, PHP snippets and search & replace. A change that can be undone answers with its undo token; `wp_undo_list` shows them, `wp_undo` reverts one.
6. Never ask the user for WordPress passwords or tokens. Sign-in happens in the browser when Cursor shows "Authenticate".
