# First Bolt — potato smoke checklist
**Owner:** CTO Sam · **No Blake wake for “does it open?”**

## Current named build
See `BUILDS.md` — live: **first-bolt-piper6-even-folio** (2026-09-17).

## One-command open
```bash
cd /workspace/lowthal-bot-wars/first-bolt-playable && python3 -m http.server 8765
```
Then open `http://127.0.0.1:8765/` (hard refresh). Or double-click `index.html`.

Optional cache-bust: `http://127.0.0.1:8765/?v=<build-slug>`.

## Smoke (Door → Folio, ~2–5 min)
Clear `localStorage` key `lowthal-first-bolt-folio-v1` first if you need a fresh Folio.

1. **Door** — pick any Path Seal door; Kin blob peeks.
2. **Mint** — share 100 across Glow · Care · Atlas (try a preset, then nudge a slider).
3. **Draft** — pick 2 supports; confirm ✓ Picked / 2 of 2.
4. **Lineup** — reorder slots; watch Edge · Even · Behind + pulse on ↑↓.
5. **Compete** — auto Soft Glow duel vs Fog Crew (no wipe).
6. **Chronicle** — one Chronicle card readable.
7. **Folio** — save; tip shows ✓ Folio saved.

**Pass:** full loop completes; Folio persists on reload of same origin.  
**Fail:** blank screen, stuck step, crash, or missing Folio tip — log in `BUGS.md`, do not wake Blake unless CoS opens an eng ticket.
