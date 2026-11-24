# Crown Siege

A real-time lane-battle card game in a single HTML file: no build step and no dependencies.

## Play

Open `index.html` in any modern browser, on desktop or mobile.

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

## Dev

`index.html?autoplay&speed=4` runs an AI-vs-AI match at 4× speed.
