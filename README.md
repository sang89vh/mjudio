# Mjudio — support pages

Legal and support pages for the [Mjudio](https://sang89vh.github.io/mjudio/) macOS app
(Music Studio Visualizer), served with GitHub Pages.

| Page | URL |
| --- | --- |
| Terms of Service | https://sang89vh.github.io/mjudio/terms |
| Privacy Policy | https://sang89vh.github.io/mjudio/privacy |
| FAQ | https://sang89vh.github.io/mjudio/faq |
| Automation API tutorial | https://sang89vh.github.io/mjudio/tutorial |
| AI assistants (macOS app) | https://sang89vh.github.io/mjudio/mcp |
| Mjudio for Windows | https://sang89vh.github.io/mjudio/windows/ |
| Windows: Automation and AI assistants | https://sang89vh.github.io/mjudio/windows/automation |
| Windows: FAQ, Privacy, Terms | https://sang89vh.github.io/mjudio/windows/faq, /windows/privacy, /windows/terms |

The first three URLs are referenced from inside the app (the paywall, Settings and the Help
menu) and are the ones App Review checks. The tutorial documents the loopback automation
API (`docs/AUTOMATION-API.md` in the app repo is its source) and nothing links to it from
the app yet. Each page is a directory with an `index.html` so the extensionless URL
resolves; keep that structure if you add pages.

The Windows app's pages live under `windows/`; its Microsoft Store listing links to
`windows/`, and `windows/automation/` documents its REST API and MCP endpoint (whose source is
`docs/AUTOMATION-API.md` §2 and §7 in the app repo, `windows` branch).

Static HTML and one stylesheet — no build step, no dependencies.
