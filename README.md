# Innsmouth Invaders

**Lovecraft Arcade Volume 2** — A retro fixed shooter inspired by Space Invaders, set on a decaying shoreline facing a hostile sea. Fend off waves of sea-born horrors and face the mighty Cthulhu.

## How to Play

Open `index.html` in any modern browser. No build step, no dependencies — just a single HTML file.

### Controls

- **Arrow Keys** — Move left/right
- **Space / Z** — Fire
- **M** — Mute/unmute audio

### Mobile

Touch controls appear automatically on smaller screens, styled with an art deco brass instrument panel aesthetic. A finger-position steering track on the left directly maps your touch position to the player, and a domed red fire button on the right handles shooting. Multitouch is fully supported — steer and fire simultaneously.

## Game Features

### Enemies

- **Ocean Crawlers** — Fish-human hybrids that shamble down from the horizon in zig-zag patterns
- **Sky Flyers** — Winged creatures that swoop in arcs across the screen before descending
- **Wharf Stalkers** — Hulking figures that emerge from the docks and drop onto the shoreline

### Boss: Cthulhu

Every 5th wave, Cthulhu rises from the ocean. Hit the head (weak point) 10 times to defeat him. He fires alternating projectile spreads from each hand and gets progressively tougher with each encounter — more minions, faster attacks, shorter cooldowns.

Watch for the damage tints: green means you're hurting him, red means he's almost done.

### Devil Reef

A distant reef on the horizon that occasionally glows. Shoot it for 500 bonus points and a chance to clear all enemies on screen.

### Wave Structure

Waves follow a 5-wave round pattern:

1. Crawlers
2. Flyers
3. Crawlers + Flyers
4. Crawlers + Stalkers
5. Boss

Each round increases enemy counts and speeds. The game scales endlessly.

### Audio

17 sound effects and 2 looping music tracks. Background music switches between normal and boss themes. Sound effects cover every action — shooting, enemy spawns, boss attacks, lightning strikes, and more. All audio files are in the `assets/` folder.

## Credits

A game by [Andrew Doss](https://www.andrewdoss.com).

Based on [*The Shadow over Innsmouth*](https://www.hplovecraft.com/writings/fiction/soi.aspx) by H.P. Lovecraft.
