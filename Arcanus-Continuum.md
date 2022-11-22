# Arcanus: Continuum

## Mana
- [x] The player starts off with 10 mana, but can grow their mana reserves up to 100 by speaking with the wizard who gives you quests.
- [x] Mana regenerates at a rate of 1 per 2 seconds by default, but can be sped up.

## Burnout
- [x] If a player doesn't have enough mana to cast a spell, they will be afflicted with burnout. Burnout will make the player more sluggish and drain their hunger rapidly, slowing down their ability to cast spells.
- [x] Burnout goes away at a rate of 1 per 4 seconds by default, but can be sped up.

## Staves
Staves are a wizard's mana focus, allowing them to cast spells to begin with.
- [ ] Wooden Staff
  - Has no bonuses, it's just a wooden staff.
- [ ] Amethyst Shard Staff
  - The target of a spell will have some of their mana drained and returned back to the caster.
- [ ] Quartz Shard Staff
  - If you're burnt out, your spells are double effective.
- [ ] Ender Shard Staff
  - ???
- [ ] Echo Shard Staff
  - Creates an echo of a spell that bypasses invulnerability frames.

## Casting
- [x] Spell casting is done by using a pattern (right and left) associated with a given spell slot on the player's staff. Each staff has 8 spell slots available to them. When you cast a spell, the player's mana is consumed and a spell is cast instantly.
- [x] If the player holds down the last button they pressed, the spell will cast in quick succession based on its cooldown.

## Enchantments
- [ ] Mana Jammer - a shield enchantment that causes spells, even shield-piercing ones, to be dispelled when coming in contact with the shield.

## Spellcraft
Spells are crafted from two main components: Spell Shapes and Spell Effects
- Spell Shapes:
  - [ ] Self - affects the caster
  - [ ] Touch - affects entities directly in front of the caster
  - [ ] Projectile - fires a fast, weightless projectile
  - [ ] Lob - launches a slow, weighted projectile
  - [ ] Bolt - fires short-range targeting bolt in front of the caster
  - [ ] Beam - forms a beam between the caster and a target, locking on and charging
  - [ ] Rune - summons a rune that effects a target upon being stepped on
  - [ ] Smite - fires down a large AOE beam from the sky
  - [ ] AOE - forms an AOE of mana around the caster
  - [ ] Void - spawns a black hole that takes a few seconds to form and start casting its effects, as well as pulling targets towards it
- Spell Effects:
  - [ ] Damage - deals damage to the target
  - [ ] Heal - heals the target
  - [ ] Fire - sets the target on fire
  - [ ] Electric - stuns the target briefly
  - [ ] Ice - makes the target cold
  - [ ] Push - pushes the target away from the caster
  - [ ] Pull - pulls the target closer towards the caster
  - [ ] Teleport - teleports the caster to the target
  - [ ] Exchange - swaps the position of the caster and the target
  - [ ] Dispel - removes all effects from the target
  - [ ] Mana Lock - locks the targets's mana, preventing them from casting spells
  - [ ] Withering - inflicts the target with wither
  - [ ] Regenerate - gives the target regeneration
  - [ ] Vulnerability - makes the target more susceptible to damage
  - [ ] Bouncy - makes the target bouncy, as if they're on slime blocks
  - [ ] Feather - gives the target slow falling
  - [ ] Power - creates a redstone signal
  - [ ] Necromancy - upon killing an entity with a spell with this mod, it will raise an undead minion
  - [ ] Mana Split - averages the caster and target's mana
  - [ ] Anonymity - makes the target anonymous by hiding the name and skin
  - [ ] Mine - mines blocks, very simple
  - [ ] Build - places the block in the caster's offhand
  - [ ] Levitate - inflicts the target with levitation
  - [ ] Transmutate - transmutates a mob into its alternate forms
  - [ ] Growth - accelerates the growth of crops and baby animals

## Structures
- [ ] Wizard Tower
  - Stands about 48 blocks tall, and houses a wizard at the top. Speaking with the wizard will initiate quests for the player to do in order to increase their mana reserves, or to upgrade their spells.

## Mobs
- [ ] Wizard
  - Neutral mob that will speak with any player wearing wizard robes.
  - Gives quests to the player to upgrade their mana reserves or their spells. Quests reset every new moon.
  - If attacked, it will attack back with magic. Can have up to 8 spells, and if killed, it will drop the spells it had and cause the tower to crumble.
