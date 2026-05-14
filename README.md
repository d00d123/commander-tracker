# Commander Tracker

**A Magic: The Gathering Commander (EDH) life tracking app — built for the table.**

Created by **Alex Branz | World Creator**

---

## Live App

[**Open Commander Tracker →**](https://d00d123.github.io/commander-tracker)

> Replace `d00d123` with your GitHub username after deploying.

---

## Features

### Core Tracking
- **2–6 players** with unique color-coded cards
- **40 starting life** with tap-to-edit life totals
- **Hold buttons** for rapid life adjustment
- **Swipe gestures** — swipe left/right on a card for −1/+1 life
- **Undo** — up to 30 steps (Ctrl+Z / Cmd+Z)
- **Auto-save** — game state persists if you close the tab

### Commander Rules
- **Commander Damage** — tracks combat damage per-attacker (21 from one commander = elimination)
- **Partner Commander support** — independent tracking for both partners
- **Commander Tax** — cast tax tracker (applies when casting from command zone only)
- **Commander Zone** — cycles In Play → Command Zone → Exile → Graveyard
- **Poison Counters** — 10 = eliminated, with fill-bar visual
- **Monarch** — transferable badge with gold pulse animation
- **Energy Counters** — per-player ⚡ tracking

### Tools
- **Dice Roller** — d2, d4, d6, d8, d10, d12, d20, d100 with roll history
- **Random Target** — slot-machine style random player selector
- **Damage All** — deal damage to every player at once
- **Activity Log** — full timestamped game history
- **Game Timer** — auto-starts, changes color at 30min / 1hr
- **Storm Counter** — shared table storm count tracker

### Visual
- Midnight purple candy-paint theme
- Player-specific color tints on each card
- Poison fill bar, CMD threat pulse, life gradient color
- Victory screen with full game scoreboard
- Collapsed tombstone view for eliminated players
- Rainbow gradient signature

### Mobile Ready
- Touch-optimised buttons (44px+ targets)
- Haptic feedback on life adjustments
- Landscape mode optimised layout
- Font size A− / A+ toggle
- PWA-ready (add to home screen in Safari)

---

## Rules Accuracy

| Rule | Implementation |
|------|---------------|
| Starting life | 40 ✓ |
| Commander damage | 21 **combat** damage from one commander ✓ |
| Poison | 10 counters = eliminated ✓ |
| Commander tax | Applies on cast from command zone only ✓ |
| Partner commanders | Each tracked independently, 21 from either = elim ✓ |
| Exile zone | Tracked separately from graveyard ✓ |

---

## How to Use

1. Select number of players (2–6)
2. Enter player names (optional)
3. Click **Begin Game**
4. Track life, commander damage, poison, and more

No installation. No account. No ads. Works offline once loaded.

---

## Deploying Your Own Copy

```bash
git clone https://github.com/d00d123/commander-tracker
cd commander-tracker
# Open index.html in any browser
```

Or enable **GitHub Pages** in repository Settings → Pages → Deploy from main branch.

---

## Tech Stack

- Pure HTML / CSS / JavaScript
- No frameworks, no dependencies
- Single self-contained file (`index.html`)
- Google Fonts (Cinzel, JetBrains Mono, Outfit)

---

## License

© 2026 Alex Branz | World Creator. All rights reserved.  
Unauthorized copying, modification, or redistribution is prohibited.
