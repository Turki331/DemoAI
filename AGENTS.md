# AGENTS.md

Stitch design export, not an app repo. Single static prototype — no build, dev server, package manager, tests, lint, CI, or git repo.

## Layout

- `code.html` — only editable UI. Self-contained (Tailwind via CDN + inline `tailwind.config` + Google Fonts). Preview by opening in a browser.
- `DESIGN.md` — token source of truth. `code.html`'s `tailwind.config` colors mirror it; keep in sync.
- `Initial_Features.md` — SaaS MVP scope (6 pages); requirements only, not implemented.
- `stitch_initial_ui_ux/` — reference multi-screen exports; read-only, do not edit.
- `screen.png` — reference screenshot of `code.html`; replace if design changes materially.
- `opencode.json` — Stitch remote MCP config only. Contains a hardcoded `X-Goog-Api-Key`; keep repo private, never commit to a public remote or log the key.
- `.gitignore` already ignores `.env` / `.env.*`; there is no env loading (`code.html` is static) — do not add `.env` unless graduating beyond prototype.
- No `README`, `package.json`, or scaffolding (Vite/Next/etc.). Do not add any unless explicitly asked.

## Conventions

- Edit `code.html` in place; keep dependency-free: CDN Tailwind + `Inter` / `JetBrains Mono` / `Material Symbols Outlined` only.
- Tokens: hairline 1px borders (`#E2E2E6`), 4px base radius / full pills, obsidian `#0D0E11` terminal panes, electric lime `#72FF13` for primary actions and active/success states with black text.
- RTL: Arabic swaps to `IBM Plex Sans Arabic`; code blocks, CLI syntax, and IDs stay `dir="ltr"`.
- Use Stitch MCP (`get_screen`, etc.) when iterating on the hosted screen instead of hand-rebuilding `code.html`.
