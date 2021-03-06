# Cammie's Combat Tweaks

## General
- [x] Attack speed now acts as a hard cooldown
- [x] Weapons attack faster than before
  - [x] Different tool materials have different attack speeds
    - [x] Wood, Stone, and Iron have the same attack speed
    - [x] Diamond is slightly slower than Wood, Stone, and Iron
    - [x] Netherite is slightly slower than Diamond
    - [x] Gold is much faster than Wood, Stone, and Iron
- [x] Gold tool durability is doubled
- [x] Undid the additional cooldown on missed attacks Mojang added in 1.8 which soft-capped CPS to 10
- [x] Item cooldown now affects attacking as well as right click
- [x] Players and Projectiles ignore invulnerability ticks
- [x] Command to get the attribute name(s) and UUID(s) on an item
- [x] An attack can now be queued when you attack while on cooldown
- [x] Removed Toughnesss and Knockback Resistance from Diamond and Netherite Armour
- [x] Players can now Crouch Jump to get a little more height

## Swords
- [x] Sword sweeping happens even if you miss an attack
- [x] Increased attack reach (from 3 to 4)

## Tridents
- [x] Increased attack reach (from 3 to 5)
- [x] Riptide works outside of water and rain
  - [x] Riptide is half as effective outside of water and rain
- [x] 25% chance to be found in place of a Treasure Map in a Shipwreck
- [x] Cap Riptide + Elytra speed to 2.5

## Crossbows
- [x] Crossbows can now have Multishot and Piercing simultaneously

## Shields
- [x] Shields can now parry direct attacks within 1/4th of a second of being used
  - [x] Parried attacks disable the attacking player's weapons for 4 seconds
  - [x] Parried attacks from non-players will deal double the damage they would deal to you
- [x] Shields now only protect in a 100 degree arc
- [x] Shields are able to block instantly
- [x] Shields now go on a 2 second cooldown if you release right click for the first half second of the shield being active
- [x] Shields only block 5 damage from direct attacks

## Armour
- [ ] Leather Armour gives 25% cold resistance
- [ ] Chainmail Armour gives 25% projectile resistance
- [ ] Gold Armour gives 25% magic resistance
- [ ] Netherite Armour gives 25% fire resistance

## Projectiles
- [x] Arrows have no random deviation
- [x] Projectiles check in a wider area for if they hit a flying player

## Potions
- [x] Speed increases air speed as well
- [x] Slowness decreases air speed as well
- [x] Regen, Poison, and Wither all have configurable timers for when they damage the player

## Enchantments
- [x] Sweeping Edge 3 multiplier is 100% base damage instead of 75%
- [x] Thorns no longer causes knockback to those hurt by it

## Regeneration
- [x] Minimum hunger for regen is 16
- [x] Player now regens at half a heart per second regardless of saturation level (configurable)
- [x] Player loses hunger at a 1:1 rate per health regenerated, instead of at a 1:1.5

## Animations
- [ ] Add proper first- and third-person attack animations for the following:
  - [ ] Sword
  - [ ] Axe
  - [ ] Trident
