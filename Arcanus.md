# Arcanus
\[insert description here\]

## Mana
Mana is a term to describe multiple types of energy that flow through ley lines in the player's body, and are utilised for magic. The player starts off with anywhere between 3-10 mana (based on the player's UUID + world seed) in each of the four types, but this number can be increased through certain actions (TBD).
- [ ] White Mana
  - Represents form and healing
  - Compliment of Black Mana
- [ ] Black Mana
  - Represents matter and creation
  - Compliment of White Mana
- [ ] Green Mana
  - Represents action and change
  - Compliment of Blue Mana
- [ ] Blue Mana
  - Represents motion and energy 
  - Compliment of Green Mana

If you have too much of one type of mana relative to its opposite, there will be negative effects induced upon the player.

## Burnout
Burnout is a negative energy that will fill the player's ley lines, resulting in a lower yield of mana, and will remain there until removed. Burnout is only gotten when you try and cast a spell without having enough of the required mana, resulting in an imbalance in energies.
<br><br>
This also causes damage to the player, relative to their maximum health. For example, if you take 20% burnout of your maximum mana in one type, you will take 20% of your health as damage. If you take 20% of your maximum mana in two types, you will take 40% damage.

## Casting
Spell casting is done by using a pattern (right and left) associated with a given spell slot on the player. The player has 8 spell slots available to them. Each spell consumes some amount of mana, depending on what components they used. Each component is associated with each mana type.

## Spellcraft
Spells are composed of different components. There's three different types of components, and components can be strung together effectively indefinitely in order to create unique spells.
<br><br>
The following are the three different types of components:
- [ ] **Shapes** - dictates how a spell effect is cast (i.e. whether it would be a projectile, affect the self, or be an area of effect)
- [ ] **Effects** - how the spell interacts with the world (i.e. setting fire to something, healing someone, or causing something to levitate)
- [ ] **Attunements** - increases aspects of the preceding Shape or Effect (i.e. making an area of effect larger or dealing more damage)
