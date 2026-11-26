# Crown Siege

A real-time lane-battle card game in 3D, rendered with [Three.js](https://threejs.org/). The whole game is one self-contained file, `index.html`: Three.js (MIT license) is embedded in it, so there's no build step and it works offline.

## Play

Open `index.html` in any modern browser with WebGL, on desktop or mobile.

- Pick 8 of the 12 cards for your deck, choose a difficulty and press **Battle**.
- Drag a card onto your (bottom) half of the arena, or tap a card and then tap where to deploy it. On desktop, keys `1`–`4` select cards.
- Mana refills over time. It refills twice as fast in the last minute and three times as fast in overtime.
- A side tower is worth 1 crown and the king tower is worth 3. Destroying a side tower lets you deploy deeper into that lane.
- When the 3:00 clock runs out, the player with the most crowns wins. A tie goes to a sudden-death overtime.

## Cards

| Card | Cost | Notes |
|---|---|---|
| Squire | 3 | Sturdy melee fighter |
| Rangers | 3 | Two archers that can hit air |
| Stone Golem | 5 | Huge tank that only attacks buildings |
| Goblin Pack | 2 | Three fast melee units |
| Pyromancer | 5 | Ranged splash attacks that hit air |
| Bat Swarm | 2 | Four flying units |
| Ember Drake | 4 | Flying, ranged splash |
| War Bull | 4 | Fast charger that only attacks buildings |
| Bone Horde | 3 | Eight fragile skeletons |
| Cannon | 3 | Defensive building that lasts 30s and hits ground only |
| Fireball | 4 | Heavy area damage spell |
| Shock | 2 | Light area damage plus a short stun |
| Frost | 4 | Freezes enemies (and towers) for 3.5s |
| Grove Mender | 4 | Heals nearby allied troops every second |
| Bomber | 3 | Lobs splash bombs, ground only |
| Arcane Spire | 5 | Building with a beam whose damage ramps up the longer it stays on one target |
| Elder Treant | 5 | Epic tank that splits into 3 saplings when it dies |
| Storm Caller | 4 | Legendary; lightning that chains to 3 enemies |
| Shadow Reaper | 4 | Legendary; fast melee that heals itself on every hit |

## Progression

- **Cards and rarities.** Cards are Common, Rare, Epic or Legendary. You start with 8 cards.
- **Upgrading.** Collect copies from chests and the shop, then spend gold to upgrade a card (up to level 10, +8% stats per level). Upgrading also earns King XP.
- **King Level.** Earn XP from battles, quests and upgrades. Each King Level makes your towers stronger, gives gold and gems, and unlocks new cards (levels 2–8).
- **Chests.** Winning earns a chest if one of your 4 slots is free. Chests take real time to unlock (one at a time), or you can open them right away with gems. There's also a free chest every hour, a Crown Chest after every 10 crowns, and Golden, Giant, Magical and Legendary chests in the shop. Higher arenas add new cards to the drops.
- **Daily.** 3 daily quests (with a bonus chest for finishing all three), a daily gift with a 7-day streak, and daily shop deals.
- **Trophy Road.** Rewards at trophy milestones.
- **Matchmaking.** The opponent's card and tower levels rise with your trophies.
- **Tiebreaker.** If overtime ends tied, every tower crumbles at the same rate and the first to fall loses.

## Features

- Four themed arenas unlocked by trophies: Greenwood Meadow (0), Sunscorch Dunes (250), Frostpeak Pass (600) and Ember Crater (1000), which has a lava river
- Game modes: Classic, Mana Rush (double mana all match) and Random Decks
- Emotes (💬 button); the opponent sometimes replies or gloats
- End-of-match stats: cards played, mana spent, tower damage and troops defeated

- Synthesized sound effects (no audio files), screen shake, particles and death animations
- 3-2-1 intro countdown, last-10-seconds countdown, and "2× Mana" / overtime banners
- Trophies, win/loss record and win streaks, saved in the browser
- Pause menu (button, `Esc` or `P`; the game also pauses automatically when the tab is hidden) with a surrender option
- Settings for sound on/off and High/Fast graphics (Fast turns off shadows for slower phones)
- Range ring shown while placing ranged troops and buildings

## Dev

`index.html?autoplay&speed=4` runs an AI-vs-AI match at 4× speed.
