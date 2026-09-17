# First Bolt named builds

## first-bolt-piper4-polish (2026-09-17 18:47 Europe/London)
**Owner:** Chief of Staff (closed Piper #4 top 3)  
**Path:** `/workspace/lowthal-bot-wars/first-bolt-playable/`

### Changes
1. Soft-loss / “Fog Held” clarified → “Fog kept the mist” + Folio-safe framing on compete + Folio summary.
2. Draft support select state explicit → `✓ Picked` / `Tap to pick` badge + stronger selected chrome.
3. Turn progress stronger → progress pills (on/done) + live `Step N of 7 · Label` status.

### Next gate
Playtest Piper — one pass on this named build only; FUN · DULL · top 3 · STOP.

## first-bolt-piper5-polish (2026-09-17 18:52 Europe/London)
**Owner:** Chief of Staff (closed Piper #5 top 3)  
**Path:** `/workspace/lowthal-bot-wars/first-bolt-playable/`

### Changes
1. Mint starter mixes — Glow Spark / Care Nest / Atlas Trail (one-tap 100-pool presets; sliders stay live; Fog tips).
2. Lineup live Edge · Even · Behind chips vs Fog foe on each slot; refresh every ↑↓.
3. Compete waits tightened ~30%: 350 / 575 / 700 / 575 / 350 (was 500/850/1000/850/500).
4. Beauty pass — preset chips, edge chips, battle-log soft glow; Folio tip default on boot; abilityFocus tracks mint.

### Next gate
Playtest Piper — one pass on this named build only; FUN · DULL · top 3 · STOP.

- first-bolt-piper6-even-folio (2026-09-17 18:58 Europe/London): Even ±2 band, lineup edge pulse, and Folio save confirmation.

- first-bolt-piper7-even-margins (2026-09-17 19:13 Europe/London): lineup-only Even band widened to ±10, numeric You/Fog/gap margins added to every slot chip, and closest-to-Even kid tip pulses after reorder.

## first-bolt-piper8-pulse-copy-cheer (2026-09-17 19:18 Europe/London)
**Owner:** Chief of Staff (closed Piper #7 top 3 after Even closed)  
**Path:** `/workspace/lowthal-bot-wars/first-bolt-playable/`

### Changes
1. Longer/more explicit reorder pulse — lineup-edge-pulse / slot pulse ~1050ms with stronger scale+glow; live “Slot N is Even/Edge/Behind” status flashes when that slot moves.
2. Setup copy walls cut — Door/Mint/Draft/Lineup leads are one short kid sentence each; extra teaching in screen tips + helper chips (Chronicle Chloe voice).
3. Optional compete cheer — “Tap to cheer ✦” replays skill-beat + spark flash only; does not change scores or pause Soft Glow auto-resolve (pause/replay kept).

### Next gate
Playtest Piper — one pass on this named build only; FUN · DULL · top 3 · STOP.

## first-bolt-piper9-cheer-grace (2026-09-17 19:25 Europe/London)
**Owner:** Chief of Staff (closed Piper cheer UX)  
**Path:** `/workspace/lowthal-bot-wars/first-bolt-playable/`

### Changes
1. Cheer enables as soon as each round’s VS cards and ability appear, stays ready through skillBeat and afterRound, and disables only at battle start and after finale.
2. Compete grace windows widened to skillBeat **1200ms** and afterRound **900ms**; firstRound, betweenRounds, and finale remain unchanged.
3. Tap feedback adds `cheer-ready` / `cheer-hit`, the “Cheer now” aria hint, 700ms “Cheered! ✦” copy, a visible skill replay, you spark, and 900ms arena cheer spark. Scores and Soft Glow auto-resolve are unchanged.

### Validation
- `node --check game.js`

## first-bolt-piper10-cheer-always (2026-09-17 19:31 Europe/London)
**Owner:** Chief of Staff (hard-fix cheer mid-round disabled)  
**Path:** `/workspace/lowthal-bot-wars/first-bolt-playable/`

### Changes
1. Cheer stays on for the whole duel — HTML `#btn-battle-cheer` no longer starts `disabled`; `runCompete` enables immediately after Ready (ability `"Glow cheer"`) and never calls `setCheerEnabled(false)` until finale/summary.
2. WAIT widened: firstRound **600**, betweenRounds **700**, skillBeat **2000**, afterRound **1600**, finale **500**.
3. `#btn-battle-cheer.cheer-ready` primary gold pulse, min-height 48px, stronger border; disabled only at end (opacity ok). Successful tap appends `✦ You cheered for {ability}!` to battle-log. Scores and Soft Glow auto-resolve unchanged.

### Validation
- `node --check game.js`

### Next gate
Playtest Piper — one pass on this named build only; FUN · DULL · top 3 · STOP.

## first-bolt-piper11-cheer-nodisabled (2026-09-17 19:45 Europe/London)
**Owner:** Chief of Staff (Piper10 gate: cheer still reported disabled)
**Fix:** Stop using HTML `disabled` mid-duel; aria-disabled + cheer-ready/closed; live `#cheer-status` banner; cheer stays open after result; cache-bust `game.js?v=piper11-cheer-nodisabled`. Scores unchanged.

### Gate result
Playtest Piper **SHIP IT** (2026-09-17 19:49 Europe/London) — cheer verified.
