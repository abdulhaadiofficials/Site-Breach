

# SITE BREACH — Final Edition

**A self-contained, single-file top-down tactical shooter.**

One HTML file. No install, no dependencies, no internet required. Open it in a browser and you're deploying.

---

## What It Is

SITE BREACH is a top-down tactical shooter where you play a lone operative breaching a 13-deck hostile facility. Every deck is a bomb-site mission: fight your way in, arm the charge at SITE A or SITE B, survive the counter-assault until detonation, and on the final deck — outrun the collapse to the extraction ring.

The whole game — landing page, engine, art, audio synthesis, campaign, progression — lives in a single `site-breach-final.html` file (v6.29 · KINETIC UPDATE). Progress, medals, rank, and settings persist in your browser via localStorage.

## How to Run It

1. Download `site-breach-final.html`
2. Open it in any modern desktop browser (Chrome, Edge, Firefox, Safari)
3. Pick a deck, pick a threat level, hit **DEPLOY**

That's it. No install, no build step, no server. Sound starts on first input (browser autoplay policy) — click or press a key once and the audio comes alive.

> **Best on desktop.** The game is built for mouse + keyboard. Hearing it matters: music, gunfire, and the low-HP heartbeat are part of the design.

## Controls

| Input | Action |
|---|---|
| **WASD** | Move |
| **Mouse** | Aim · **Hold LMB** to fire |
| **Shift** | Sprint |
| **Space** | **Dash** — 2 charges, 9s recharge, brief invulnerability frames |
| **E** (hold) | Plant / arm the charge · transfer through vents |
| **R** | Reload |
| **1–5** | Select weapon: PISTOL · SMG · SHOTGUN · RIFLE · MAGRAIL |
| **G** | Throw frag grenade |
| **F** | Throw flashbang |
| **T** | Throw smoke |
| **C** | Deploy sentry kit (upgrades friendly sentries into TWIN-LINKs) |
| **V** | Melee |
| **P / Esc** | Pause (resume · redeploy · settings · abort) |
| **M** | Mute / unmute |

## Feature Rundown

**13 decks, one campaign.** From THE YARD to THE ORBITAL — a derelict space station that never deorbited — each deck has its own layout, roster, and mission rules: hunt decks where sites stay locked until the HVT drops, twin-charge decks that demand both sites be armed, live-alarm holdouts, and an escape finale on Deck 13.

**15 hostile classes.** Sentries, roamers, snipers, heavies, shield bearers, medics that heal what you wound, pyros, spitters, sappers, EMP-firing techs — and DRONES, quad-rotor hunter-killers that weave in and dart at you. Deck 08 hides **SUBJECT NULL**, a three-phase apex boss. High-value targets have personalities: the CURATOR releases drone swarms below half health, the KEYHOLDER seals the vents, the FOREMAN rolls with shield bodyguards.

**Medals & rank progression.** 24 commendations — from FIRST BLOOD and UNTOUCHABLE to GUN FU, PHANTOM STEP, and CAMPAIGN COMPLETE — displayed in an in-game medal case. Every run pays out XP with a full debrief breakdown; climb the ranks from R-01 up.

**Style scoring.** The game pays aggression: close-range kills, knife kills, swap combos, and multi-kill chains all feed the rating. Chain three kills and time dilates — kill-chains trigger slow-motion with muffled audio, and the breach moment itself does too.

**The dance button.** SPACE dash with i-frames, pip-charges under your operative. Dodge the slasher's lunge, sidestep the pyro's flame lock, dash through the blast wave.

**Staged climax.** The moment the charge is armed, the deck changes: a counter-assault wave at 20 seconds, the final rush at 10, fire crawling toward the charge, red strobe. Win it standing.

**Death recap.** Die and the debrief tells you exactly what got you — who dealt the damage, and how much — plus counter-advice for next time.

**Everything else in the file:** killcams, dynamic music that reacts to alarm state, daily mutators, difficulty tiers from RECRUIT up, a settings panel (audio buses, screen shake, damage numbers), and a settings/persistence layer that survives reloads.

---

*Single file · ~10,000 lines · no external assets — every sprite, sound, and system is generated in-file.*
