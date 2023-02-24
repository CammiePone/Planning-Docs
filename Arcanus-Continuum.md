# Arcanus: Continuum

## Mana
- [x] The player starts off with 10 mana, but can grow their mana reserves up to 100 by speaking with the wizard who gives you quests.
- [x] Mana regenerates at a rate of 1 per 2 seconds by default, but can be sped up.

## Burnout
- [x] If a player doesn't have enough mana to cast a spell, they will be afflicted with burnout. Burnout will make the player more sluggish, slowing down their ability to cast spells and move.
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
  - Halves the mana cost for movement-based spells.
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
  - [x] Self - affects the caster
  - [x] Touch - affects entities directly in front of the caster
  - [x] Projectile - fires a fast, weightless projectile
  - [x] Lob - launches a slow, weighted projectile
  - [x] Bolt - fires short-range targeting bolt in front of the caster
  - [x] Beam - forms a beam between the caster and a target, locking on and charging
  - [x] Rune - summons a rune that effects a target upon being stepped on
  - [x] Smite - fires down a large beam from the sky that hits everything from the ground to world height
  - [x] AOE - forms a persistent AOE effect around the caster
  - [x] Explosion - causes an explosion with the caster at the epicenter
- Spell Effects:
  - [x] Damage - deals damage to the target
  - [x] Heal - heals the target
  - [x] Fire - sets the target on fire
  - [x] Electric - stuns the target briefly
  - [x] Ice - makes the target cold
  - [x] Push - pushes the target away from the caster
  - [x] Pull - pulls the target closer towards the caster
  - [x] Teleport - teleports the caster to the target
  - [x] Exchange - swaps the position of the caster and the target
  - [x] Dispel - removes all effects from the target
  - [x] Mana Lock - locks the targets's mana, preventing them from casting spells
  - [x] Withering - inflicts the target with wither
  - [x] Regenerate - gives the target regeneration
  - [x] Vulnerability - makes the target more susceptible to damage
  - [x] Fortify - makes the target less susceptible to damage
  - [x] Bouncy - makes the target bouncy, as if they're on slime blocks
  - [x] Feather - gives the target slow falling
  - [x] Power - creates a redstone signal
  - [x] Necromancy - upon killing an entity with a spell with this mod, it will raise an undead minion
  - [x] Mana Split - averages the caster and target's mana
  - [x] Anonymity - makes the target anonymous by hiding the name and skin
  - [x] Mine - mines blocks, very simple
  - [x] Build - places the block in the caster's offhand
  - [x] Levitate - inflicts the target with levitation
  - [x] Growth - accelerates the growth of crops and baby animals

## Structures
- [x] Wizard Tower
  - Stands about 48 blocks tall, and houses a wizard at the top. Speaking with the wizard will initiate quests for the player to do in order to increase their mana reserves.

## Mobs
- [ ] Wizard
  - Neutral mob that will speak with any player wearing wizard robes.
  - Gives quests to the player to upgrade their mana reserves or their spells. Quests reset every new moon.
  - If attacked, it will attack back with magic. Can have up to 8 spells, and if killed, it will drop the spells it had.
- [x] Opossum
