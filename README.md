# Lowthal Bot Wars — First Bolt (playable)

Self-contained offline prototype. **No build step.** Open `index.html` in any modern browser.

## How to open

1. Go to this folder: `lowthal-bot-wars/first-bolt-playable/`
2. Double-click **`index.html`**, or from a terminal:
   ```bash
   # from this folder
   python3 -m http.server 8765
   # then visit http://localhost:8765
   ```
3. Play end-to-end (~5–10 min). Folio saves to **localStorage** on this device.

Files: `index.html` · `styles.css` · `game.js`

## What you play

1. **Door** — pick 1 of 4 witch/wizard doors; Tide-Mark Kin blob peeks and reacts.
2. **Mint** — share **100** between **Glow · Care · Atlas** so each gets a little bit and none hogs the whole pie; cool ability name comes from the door seal.
3. **Draft** — pick **2** Folio supports from a tiny preset list (Echo fantasy + Chronicle honesty line).
4. **Lineup** — reorder slots **1–2–3**.
5. **Compete** — auto-resolve vs **Fog Crew** (round-by-round soft Glow duel + why summary). No lethal wipe.
6. **Chronicle Shelf** — one short Chronicle card.
7. **Folio** — save squad to localStorage; replay anytime.

## Cupcake → Lowthal map (no trademarks in-game)

| Cupcake / Arena beat (Day 2) | First Bolt |
|---|---|
| Marketplace template → character | Path Seal / Echo door → **Kin Bot** face |
| CHA / DEX / INT pool 100 | **Glow · Care · Atlas** pool 100 |
| Draft ~3 + set lineup | Kin + **2 supports**; lineup order |
| Compete, auto-resolve (Super Auto Pets vibe) | Soft **Glow** duel vs Fog Crew + animation/summary |
| Replay / summary | Afterglow summary + optional replay |
| Rarity boosts pool; anti pay-to-win | Door gift only here; quest rarity later — **no loot boxes** |
| Cool ability names | Seal abilities (e.g. Moonfoam Pulse, Kindstitch) |
| Blob chassis / holo cards | Colorful bar-eye blobs + light holo chrome |

Evidence for the locked Cupcake loop: `../cupcake-specimen/LOOP-FROM-DAY2.md` (timestamped cites from `day2-named-transcript.txt`).

## Design rules (Harry)

- Remix Cupcake loop — **not** restaurant OS, **not** bot-wars.vercel.app.
- Ages **7–22** layered (kid-clear copy).
- **Chronicle vs Legend** honesty on cards.
- Soft win only; cosmetics OK later; never pay-to-win.
