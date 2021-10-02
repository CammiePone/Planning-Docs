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
- [x] Players, Projectiles, and Magic ignore invulnerability ticks

## Damage Types
- [ ] 4 different DamageTypes certain weapons inflict
  - [ ] Piercing - applies to Arrows and thrown Tridents
  - [ ] Bludgeoning - applies to Shovels, Pickaxes, and swung Tridents
  - [ ] Cleaving - applies to Axes and Hoes
  - [ ] Slashing - applies to Swords

## Swords
- [ ] Swords now act as an active hitbox when swung, but they can only hit an entity once
- [ ] Increased attack reach (from 3 to 4)

## Tridents
- [ ] Increased attack reach (from 3 to 5)
- [ ] Riptide works outside of water and rain
  - [ ] Riptide no longer works for Elytras unless in the water or rain
- [ ] Increased drop chance


## Crossbows
- [x] Crossbows can now have Multishot and Piercing simultaneously

## Armour
- [ ] Different armours will resist different DamageTypes
  - [ ] Armours will also be weak to certain DamageTypes
- [ ] Armour protection will be nerfed a little bit

## Shields
- [x] Shields can now parry direct attacks within 1/4th of a second of being used
  - [x] Parried attacks disable the attacker's weapons for 4 seconds
- [x] Shields now only protect in a 100 degree arc
- [x] Shields are able to block instantly
- [x] Shields now go on a 2 second cooldown if you release right click for the first half second of the shield being active
- [x] Shields only block 5 damage from direct attacks

## Elytras
- [ ] Increased hitbox (collision box remains the same) size while in use
