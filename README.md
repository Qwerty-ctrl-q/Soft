# Monster Run

A single-file HTML5 canvas survivors-like — a fan remake inspired by the gameplay of Mattle Run (guest.mattle.fun).

**Play:** open `index.html` in any browser. No build, no dependencies — everything (pixel font, sprites, sound) is generated or embedded in the one file.

## Features

- 6 modes: **Normal**, **Hard**, **Cursed** (wizards), **Endless** (survive forever, biomes rotate every 2 min), **Boss Rush** (a boss every minute), **Gold Rush** (x6 coin drops)
- 4 biomes/locations: dirt, snow, lava, swamp
- A 100-mission campaign line with varied objectives (kill counts per monster type, boss hunts, mode wins, no-hit runs, evolutions) and growing coin rewards
- Every monster type drops its own gem color
- 10 playable heroes of different races (Mate, Ninja, Robot, Ghost, Demon, Alien, Skeleton, Golem), each a full humanoid pixel character with race outfit, held weapon and a 4-frame walk cycle, Health/Armor/Speed/Luck traits, a unique starting weapon and a unique perk (regeneration, undead second life, pyromania, fast dash, etc.)
- 12 auto-attacking weapons with 16 upgrade levels each: Knife, Machete, Sword, Bat, Shuriken, Grenade, Bazooka, Molotov, Laser, Drone, Frost Aura, Orbital
- 11 passives: Damage+, Speed+, Health+, Armor+, Magnet+, Cooldown+, Luck+, Area+, Amount+, Crit Chance+, Crit Damage+
- Weapon evolutions: max a weapon (lv.8) while holding its paired passive, then grab the chest from an elite/boss (e.g. Sword -> Excalibur, Grenade -> Cluster Bomb)
- Dash on Space (touch: DASH button) with i-frames and cooldown
- Horde events every 2 minutes: the timer flashes red and a wall of fast monsters floods in
- Crit system, elite auras, up to 6 weapon + 6 passive slots
- Level-up card picker with reroll, XP gems, magnet radius
- 15 monster types with distinct behaviors (exploding bombers, speedy wasps, dark shades, rock golems, splitting slimes, phasing ghosts...) (splitting slimes, phasing ghosts, burst-moving spiders, wobbling bats, tanky brutes), elites every minute, mini-bosses every 2.5 minutes, and three distinct bosses per run: Crab King, orb-casting Wizard King and the final Demon
- Consumables: potion, magnet, bomb (keys 1/2/3)
- Chiptune music + SFX (WebAudio), pause, FPS/monster counters
- Win/Game-over screen with points, coins earned, completed missions/achievements and local best-score records
- Meta progression: coins drop from monsters and elites, 6 of the 10 heroes are unlocked with coins (300-1000c)
- Rotating missions (3 active, endless tiers with growing targets and rewards) with a live in-run tracker
- 30 achievements and a profile stats panel (GOALS button on the title screen)
- Keyboard (WASD/arrows) and touch (virtual joystick) controls

## Controls

| Input | Action |
|---|---|
| WASD / arrows / touch drag | move |
| Space / DASH button | dash |
| 1 / 2 / 3 | use potion / magnet / bomb |
| P / Esc | pause |
| R (on game over) | retry |
