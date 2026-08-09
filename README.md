# Games

## INK DREAM

A single-file monochrome point-and-click puzzle game inspired by the mechanics of
HER TREES : PUZZLE DREAM (an original fan-style homage — own art, own puzzles).
Drag and combine objects; the right overlap reveals hidden letters, letters form
codes, codes open doors deeper into the dream. 3 zones, 9 puzzles, 3 codes,
hint system, autosave, WebAudio sound.

**Play:** open `ink-dream.html` in any browser (mouse or touch).

Full research/analysis of the original game: `her-trees-puzzle-dream-analysis.md`.

## Monster Run

A single-file HTML5 canvas survivors-like — a fan remake inspired by the gameplay of Mattle Run (guest.mattle.fun).

**Play:** open `index.html` in any browser. No build, no dependencies — everything (pixel font, sprites, sound) is generated or embedded in the one file.

## Features

- 3 modes: **Normal** (10 min, 1000 pts win bonus), **Hard** (5 min, 120% pace, 4000 pts), **Cursed** (10 min, 80% stats, 1500 pts, wizard monsters)
- 4 playable mates (Purple / Blue / White / Black) with Health, Armor, Speed and Luck traits and unique starting weapons
- 12 auto-attacking weapons with 8 upgrade levels each: Knife, Machete, Sword, Bat, Shuriken, Grenade, Bazooka, Molotov, Laser, Drone, Frost Aura, Orbital
- 11 passives: Damage+, Speed+, Health+, Armor+, Magnet+, Cooldown+, Luck+, Area+, Amount+, Crit Chance+, Crit Damage+
- Weapon evolutions: max a weapon (lv.8) while holding its paired passive, then grab the chest from an elite/boss (e.g. Sword -> Excalibur, Grenade -> Cluster Bomb)
- Dash on Space (touch: DASH button) with i-frames and cooldown
- Horde events every 2 minutes: the timer flashes red and a wall of fast monsters floods in
- Crit system, elite auras, up to 6 weapon + 6 passive slots
- Level-up card picker with reroll, XP gems, magnet radius
- Monster waves that scale over time, elites every minute, mid-run boss and final boss
- Consumables: potion, magnet, bomb (keys 1/2/3)
- Chiptune music + SFX (WebAudio), pause, FPS/monster counters
- Win/Game-over screen with points and local best-score records
- Keyboard (WASD/arrows) and touch (virtual joystick) controls

## Controls

| Input | Action |
|---|---|
| WASD / arrows / touch drag | move |
| Space / DASH button | dash |
| 1 / 2 / 3 | use potion / magnet / bomb |
| P / Esc | pause |
| R (on game over) | retry |
