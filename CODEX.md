# Frontend Slides for Codex

A Codex-compatible packaging layer for `zarazhangrui/frontend-slides`.

This fork adds:

- `.agents/plugins/marketplace.json` for Codex local marketplace discovery.
- `plugins/frontend-slides/.codex-plugin/plugin.json` for Codex plugin metadata.
- Codex wording in the `frontend-slides` skill where the original extension referenced Claude-specific tools and scratch paths.

The original skill payload remains under `plugins/frontend-slides/skills/frontend-slides/` and keeps the upstream workflow for building zero-dependency HTML slide decks, converting PPTX files, deploying to Vercel, and exporting PDFs.
