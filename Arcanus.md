# Arcanus

## Mana
The player starts off with 10 mana, but can grow their mana reserves up to 100 by speaking with the wizard who gives you quests.
- Mana regenerates at a rate of 1 per 2 seconds by default, but can be sped up.

## Burnout
If a player doesn't have enough mana to cast a spell, they will be afflicted with burnout. Burnout will make the player more sluggish and drain their hunger rapidly, slowing down their ability to cast spells.
- Burnout goes away at a rate of 1 per 4 seconds by default, but can be sped up.

## Staves
Staves are a wizard's mana focus, allowing them to cast spells to begin with.
- Wooden Staff
  - Has no bonuses, it's just a wooden staff.
- Amethyst Shard Staff
  - The target of a spell will have some of their mana drained and returned back to the caster.
- Quartz Shard Staff
  - The target of a spell gets set on fire (or soul fire if it's a fire-based spell).
- Ender Shard Staff
  - Teleports the target of a spell, with a random camera yaw.
- Echo Shard Staff
  - Creates an echo of a spell that bypasses invulnerability frames.

## Casting
Spell casting is done by using a pattern (right and left) associated with a given spell slot on the player's staff. Each staff has 8 spell slots available to them. When you cast a spell, the player's mana is consumed and a spell is cast instantly.
- If the player holds down the last button they pressed, the spell will cast in quick succession based on its cooldown.

## Spellcraft
Spell come in the form of spell books. Each spell has a base form, and then 3 optional side-grades.
- Magic Missile - fires a magical projectile that deals damage.
  - Piercing Arrow - fires a magical arrow that pierces entities and shields.
  - Stinging Shot - launches a multiple low-damage magical projectiles that ignores invulnerability ticks. Magical shotgun.
  - ??? - ???
- Incinerate - sets things on fire in a cone in front of the player. Ignites entities.
  - Immolate - creates a piercing stream of fire in front of the player. Ignites entities.
  - Fireball - launches a fireball in the direction the player is looking. Ignites entities and blocks.
  - Flame Pillar - creates a pillar of fire that incinerates anything that hits it. Ignites entities and blocks.
- Spark - creates electrical arcs all around the player, stunning anything it hits for a short while.
  - Lightning Bolt - a directional bolt of electricity that deals a lot of damage.
  - Shocking Arc - creates a weak bolt of electricity that arcs between up to 5 entities, stunning them for a short while.
  - ??? - ???
- Healing Touch - heals the caster or any entity they're looking at for 5 HP.
  - Invigorating Aura - heals any entities that stand inside the sigil for 1 HP per second. Lasts for 10 seconds.
  - Rejuvination Orb - attaches to an entity and heals them for 2 HP per second. Lasts for 10 seconds.
  - Vampiric Orb - attaches to an entity and saps their heal to the caster at a rate of 1 HP per second. Lasts for 5 seconds.
- Summon Fangs - summons a line of evoker fangs that bite any entity caught in them.
  - Summon Vex - summons a Vex to fight on behalf of the caster.
  - Summon Clone - summons a clone of the caster that runs in the direction the caster was looking until it hits a wall or gets hit. Renders the caster invisible until the clone disappears.
  - ??? - ???
- Mana Burst - creates a very powerful explosion of raw mana from the caster's feet. Imparts some mana on all targets.
  - Solar Strike - calls down a massive beam of mana from the sky upon a target. Imparts some mana on all targets.
  - Mana Sphere - launches a fast-moving projectile of raw mana that deals a lot of knockback. Imparts some mana on its target.
  - Mana Bolt - fires out a bolt of raw mana that pierces multiple entities and their armour. Imparts some mana on all targets.

## Structures

## Origin
