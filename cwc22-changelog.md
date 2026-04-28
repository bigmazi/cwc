# Custom Weapons: Classy v2.2

Hopefully, it will have been worth the wait!

- NEW WEAPONS! Lot's of them!
- Entire TF2 inventory is fully available now.
- The porting is complete: every CW:Classy item that was not ported until now is now once again in the mod.

# New weapons

- **Shrapnel** for Scout
- **Machine Pistol** for Scout
- **Flag** for Soldier
- **Molotov** for Pyro
- **Aerial Bomb Launcher** for Demoman
- **Pipebomb Launcher** for Demoman
- **Cluster Munitions** for Demoman
- **Rocket Barrage** for Heavy Weapons Guy
- **Artillery Mini-Sentry Guns** for Engineer
- **Healing Mini-Sentry Gun** a.k.a. **Robo-Doctor on Duty** for Engineer
- **Shard of Crusader's Sword** for Medic
- **Marksman Rifle** for Sniper
- **Attachable Scope** for Sniper
- **Explosive Bullets** for Sniper
- **Survival Kit** for Sniper
- **Venomous Spider** for Sniper
- **Taser** for Spy

# Changelog
## Scout
### Ricochet
- Vintage version a.k.a. ~~**Winn's Lever**~~ is retired. The weapons once again has the appearance of a pitching machine.
- Massive change to the stats; now the weapon is sort of a merge between vintage and non-vintage versions (with a cherry on the top!).
- Projectile is unaffected by gravity.
- Without bonus: 20 base damage regardless of distance.
- With bonus: 50 base damage, 0.75 falloff-over-distance multiplier, 1.75 rampup-over-distance multiplier.
- Now ricochet will also mini-crit (on top of bonus damage) when it's not from the floor.
- 0.5s attack interval.
- Reload speed matches that of stock Scattergun.
- Updated model.
- Refined sound effects.
- Now uses different crosshair.

### Lucky Strike
- New sound effects.
- New animations.

### ~~S.T.E.N.~~
- **Ported**.
- Name dropped in favor of plain **Burst-Mode SMG**.
- No longer requires attack button to be held during the burst. Single tap will always make the weapon shoot until the burst is over.
- Now sounds & muzzle flashes are predicted perfectly by the client.
- Massive change to the stats. Notably, burst & attack interval are significantly shorter but less damage per burst and significantly less damage per shot (and per burst therefor) at long distances.
- 24 rounds per clip. 4 rounds per burst. 2 bullets per shot.
- 7.5 base damage per bullet (i.e. 15 per shot). 0.2 falloff-over-distance multiplier, 1.75 rampup-over-distance multiplier.
- Time interval between bursts: 0.55s (i.e. between the first shot of the first burst and the first shot of the second burst).
- Time interval between shots within a burst: 0.05s.
- New sound effects.
- Now ejects shells.
- Now uses different crosshair.

### ~~Extra Shot~~
- Name dropped in favor of plain **Microshotgun**.

### Bucket
*No changes*.

## Soldier
### Anti-Materiel Rifle
- Adjusted damage numbers (unchanged at no charge, more damage at long range with full charge, less damage at close range with full charge).
- Direct hits now cause projectile to explode. Blast damage is unaffected by the charge. May cause self-damage.

### Airburster
*No changes*.

### Bolt-Action Rifle
*No changes*.

### Remote Control
*No changes*.

## Pyro
### Thermite Cannon
- Significantly reduced the duration of afterburn per damage instance. Now it's sort of close to how stock Flamethrower inflicts afterburn: the longer victim gets damaged, the longer they burn.
- New model.
- As per traditions, completely new visual effects.
- Death from impact now uses a separate killfeed icon.

### Lightning Gun
***Ported** without changes.*

### Fireworks
- This weapon will not auto-holster when out of ammo (i.e. you can use its altfire for blast jumps even when it's empty).
- Blast damage is now considered to be of the fire type.
- New projectile model.
- New visual effects.

## Demoman
### Pumpkin Action
- When a pumpkin double donk occurs, it is now properly announced with the expected sound and the expected sign above the victim's head.
- The fact that this weapon can double donk is now explicitly stated in the description.
- Impact damage is now considered to be of the explosive type.
- New model for small pumpkins.
- Refined animations.
- New killfeed icons for new ways to combo this weapon, he-he.

### Explosive Crossbow
- Slightly reduced self-damage to match that of stock Grenade Launcher (it's 75 now).

### Degroot Reserve
*No changes*.

### Cigar
*No changes*.

## Heavy Weapons Guy
### Mortar
- Bombs no longer ricochets. It was fun! But the experiment is over.
- New model. With spinning parts!
- Now emits revving sounds.
- Rewritten description.

### Sewing Machine
- New model.
- New muzzle flash**es**. One for each barrel!

### Chainsaw
- **Ported**.
- Significantly simplified impact effects. They're just small & silent sparks now.
- Adjusted damage. It no longer depends on distance.
- Significantly improved accuracy.
- Reduced range.
- The teeth are now properly animated.

## Engineer
### Hookshot
- The reel is now properly animated and serves as a cooldown cue. It won't stop spinning until the hook cools down.
- Even more cues: the grappling hook visually disappears from weapon model until it can be fired again.

### Paint Sprayer
- **Ported**.
- Ignition now deals 40 damage (2s cooldown per victim; i.e. if you ignite someone, you deal 40 damage, then you will be able to deal these 40 damage again after 2 seconds pass).
- Refined hit registration.

### Packed Jet
- Stomp damage now matches that of Mantreads (except for Hookshot grapple into stomp combo which is still 30 + 60 = 90 damage).

### ~~Mini Set~~
- **Ported**.
- Reworked into **Mini-Dispenser** which now occupies secondary slot.
- Now grants an extra building (mini-dispenser and nothing else) without replacing anything (note that it is even available to Engineers with Packed Jet equipped!).
- Mini-Dispenser no longer self-destructs.
- Health & ammo resupply power of Mini-Dispenser is demoted to that of LVL1. Still doesn't generate metal.
- Mini-Dispenser now costs 100 metal.

## Medic
### ~~Overdose MkII~~
- Name dropped in favor of plain **Syringe Shotgun**.
- Refined sound effects.

### Salutary Serum
- The max amount of bottles is increased to 12 (was 6).
- Slightly increased the linger duration for the bottles that are marked for destruction (happens when Medic attempts to place 13th bottle).
- Note that Overdose & Ubersaw treats Salutary Serum alt-fire charge level as ubercharge level for their bonuses.

### Life Stealer
- It is now filled with liquid. At last! The liquid level correlates with Medic's health.

### Defibrillator
- **Ported** & substantially reworked.
- Damage no longer depends on charge. It's always 65 now.
- Ability to boost with mini-crits no longer has cooldown. Instead, it consumes 5% of ubercharge.
- Now decreases ubercharge gain by 15% (affects Salutary Serum as well).

## Sniper
### Harpoon Gun
- Fully charged shots no longer have range cap.

### Soviet Classic
- **Ported**.
- No longer comes with a suit. Make one yourself!

### Shredder
- **Ported**.
- Refined animations.
- No longer comes with a suit. Make one yourself!

### J.A.M.
*No changes*.

### Carbine
- **Ported**.
- Refined animations.

## Spy
### Pocket Accelerator
- Slightly increased debuff linger duration after unscoping (now equals 0.25s)
- Now has a red skin. At last!
- Removed muzzle flash.
- Note that Dead Ringer may be used to fake gun breaking.
- Note that Only Dead Ringer and ubercharge may save Spy from lethal damage of gun breaking. Resistances are ignored.

### Smoke Bomb
*No changes*.

### Last Vaccination
- The syringe now appears as emptied during backstab animation. Guess where that green substance goes, huh!
- Refined texture.
- Note that Diamondback grants a crit once backstabbed victim dies (regardless of what kills them).

### Red Button
- Special voice line under *a particular effect* is back ;)
- Note that Diamondback grants a crit for each enemy killed by this weapon.

## Multi-Class
### ~~Oppressor's Suppressor~~
***Ported** but temporarily disabled*.

### ~~Whipper-Snapper~~
***Ported** but temporarily disabled*.
