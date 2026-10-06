# CLAUDE.md

Concise working notes. Replace stale info, don't append. Full rules are in `AGENTS.md`.

## What this is
JohnAyo's single-file portfolio (`index.html`), vanilla HTML/CSS/JS, no build. Red-neon, liquid-glass style inspired by Tobiloba Jagun's portfolio (used with permission).

## Every session
1. Read `AGENTS.md` and the end of `handoff.md`.
2. Edit `index.html` (and `avatar-ascii.js` for the hero portrait) unless told otherwise. Small patches, never a full rewrite.
3. After changes: verify section ids intact, no console errors, mobile width OK, reduced-motion OK.
4. Log what changed in `handoff.md` and update this file if you learned something.

## Current state
- Done: neon red palette, liquid glass, ASCII avatar (`avatar-ascii.js`), progress bar, solar system, experience stack, tilt/spotlight/magnetic hover.
- Pending: 5 project screenshots (`assets/projects/image.md`), optional real dates on experience cards (ask JohnAyo, don't guess).
- Not yet browser-tested by Claude: confirm visually after any change.

## Watch out
- `--gold` = red and `--cyan` = ember now. Don't "fix" the names.
- Solar planets come from `.inv-slot` chips. Edit the chips, not the JS.
- Chromium-only glass warp; fallback is blur.
- No invented content. Ask before adding claims.
