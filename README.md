# Seven Proofs: Porto Novo — Web Build

Playable web (HTML5/WASM) build of *Seven Proofs: Porto Novo*, exported from Godot 4.7.

**Play:** https://apuruni.github.io/seven-proofs-web/

This repo hosts only the exported build — the no-threads variant, so it runs on
GitHub Pages, which cannot send the COOP/COEP headers the threaded build needs.
Game source and the design document live in the private `apuruni/seven-proofs` repo.

Kept for future integration work (decided 2026-11-14).

To refresh the build: in the source project, export with the "Web" preset in
`export_presets.cfg`, with `variant/thread_support=false` for Pages hosting
(the threaded variant works on hosts that send Cross-Origin isolation headers).
