# Devotion

## Casting System
- [ ] Casting is handled by selecting a spell in a radial menu, setting the player's Spell Charge to the selected spell.
  - [ ] The player's Spell Charge will display at the bottom right side of the screen.
  - [ ] The player can open the spell selection screen by holding Right Click while holding a wand, and select a spell by mousing over it and letting go of Right Click.
  - [ ] The player can cast their Spell Charge by Left Clicking.
- [ ] Spells have 3 levels of complexity, each consuming a certain amount of aura:
  - [ ] Simple (1 aura)
  - [ ] Intricate (2 aura)
  - [ ] Complex (3 aura)
- [ ] There are also Unique spells, which will drain a player's Aura at a rate of 1 per second.

## Research System
- [ ] Research is done by giving players a 6-dot grid in the shape of a pentagon with one dot in the middle, representing the Aura Diagram abstractly. The player is also provided with a 6 line riddle, where each line describes one of the Aura Types. Connecting the dots in the order provided by the riddle will complete the research.
  - [ ] To make it easier to connect the dots, so to speak, there will be an Aura Diagram behind the riddle text as decoration on the book's page.
  - [ ] Doubles as a way to get players familiar with the Aura Types so when they want to suggest spells, I don't have to tell people that the spell they're suggesting doesn't fit the category they think it fits.

## Arcane Altar
- [ ] A moderately sized structure that uses the latent magical power held within Amethyst Clusters to execute rituals.
  - [ ] These rituals include:
    - [ ] Reinvigorating the player's Aura
    - [ ] Selecting the player's Aura Type
    - [ ] Adding spells to the player
    - [ ] Crafting magical items
    - [ ] Accessing the US nuclear weapons launch codes
  - [ ] When activated, the pool will glow as magical energy from the ring of Amethyst Clusters is pulled into the central Amethyst Cluster. Once the amethyst is consumed, the items in the central block in the pool (currently represented by a Purpur slab) will be subsumed into the central Amethyst Cluster as well. From there, it will begin to glow with Aura for a few seconds before the ritual is completed.
    - [ ] If the player is attaching a spell, ending the ritual will present the player with a screen of their spell slots and the spell(s) they wanted to use. They just drag and drop it into the desired slot.
- <details>
    <summary>Appearance</summary>
    <p>The water would normally be matching purple to the amethyst, as it's been discoloured by the crying obsidian.</p>
    <img src="https://user-images.githubusercontent.com/16853086/161438084-2f449b32-8f34-4ecd-abb0-3f48345fa389.png">
  </details>

## Items
- [ ] Potion Belt

## Aura Types
- [ ] Spells fall into one of 6 Aura Types:
  - [ ] Enhancement - uses aura to increase the natural abilities of the body.
    - <details>
        <summary>Proficiencies</summary>
        <ul>
          <li>Enhancement Proficiency:   100%</li>
          <li>Transmutation Proficiency: 80%</li>
          <li>Emission Proficiency:      80%</li>
          <li>Conjuration Proficiency:   40%</li>
          <li>Manipulation Proficiency:  40%</li>
        </ul>
      </details>
  - [ ] Transmutation - changes the properties of aura to mimic something else.
    - <details>
        <summary>Proficiencies</summary>
        <ul>
          <li>Enhancement Proficiency:   80%</li>
          <li>Transmutation Proficiency: 100%</li>
          <li>Emission Proficiency:      40%</li>
          <li>Conjuration Proficiency:   80%</li>
          <li>Manipulation Proficiency:  40%</li>
        </ul>
      </details>
  - [ ] Emission - separates aura from the body and uses it as projectiles.
    - <details>
        <summary>Proficiencies</summary>
        <ul>
          <li>Enhancement Proficiency:   80%</li>
          <li>Transmutation Proficiency: 40%</li>
          <li>Emission Proficiency:      100%</li>
          <li>Conjuration Proficiency:   40%</li>
          <li>Manipulation Proficiency:  80%</li>
        </ul>
      </details>
  - [ ] Conjuration - creates physical objects out of aura.
    - <details>
        <summary>Proficiencies</summary>
        <ul>
          <li>Enhancement Proficiency:   40%</li>
          <li>Transmutation Proficiency: 80%</li>
          <li>Emission Proficiency:      40%</li>
          <li>Conjuration Proficiency:   100%</li>
          <li>Manipulation Proficiency:  80%</li>
        </ul>
      </details>
  - [ ] Manipulation - controls physical things (animate or inanimate).
    - <details>
        <summary>Proficiencies</summary>
        <ul>
          <li>Enhancement Proficiency:   40%</li>
          <li>Transmutation Proficiency: 40%</li>
          <li>Emission Proficiency:      80%</li>
          <li>Conjuration Proficiency:   80%</li>
          <li>Manipulation Proficiency:  100%</li>
        </ul>
      </details>
  - [ ] Specialist - powerful spells that don't fit into any other category.
- [ ] Players can give themselves proficiency with one of the 5 Aura Types (not Specialist) through a ritual.
  - <details>
      <summary>If the player has no selected proficiency, their spread is as follows:</summary>
      <ul>
        <li>Enhancement Proficiency:   50%</li>
        <li>Transmutation Proficiency: 50%</li>
        <li>Emission Proficiency:      50%</li>
        <li>Conjuration Proficiency:   50%</li>
        <li>Manipulation Proficiency:  50%</li>
      </ul>
    </details>

## Aura
- [ ] The player has 20 aura available to them.
- [ ] Aura regenerates at a rate of 1 per minute.
- [ ] Aura can be fully regenerated by sleeping or doing a ritual to reinvigorate the player's aura.
- [ ] Aura can be regenerated faster by consuming a Potion of Rejuvination.
  - [ ] Potions of Rejuvination are made with the same ritual used to reinvigorate the player's aura (might not happen, depends on how strong spells are).

## Spell Slots
- [ ] Spell slots are directly attached to the player.
- [ ] The player starts with 2 spell slots, and can gain more (up to 10) through mastering magic.

## Spells
- [ ] Enhancement Spells
  - [ ] Healing Hand (Simple)
    - Heals yourself, or others you touch, by 5 health.
  - [ ] Agile Strikes (Simple)
    - Increases your mining and attack speed by 25%.
  - [ ] Iron Skin (Intricate)
    - Decreases incoming damage by 5.
  - [ ] Heavy Weight (Intricate)
    - Immune to knockback and you deal damage to entities you fall on.
  - [ ] Full Cowl (Complex)
    - Increases the player's speed, jump height, and damage for a short period of time.
  - [ ] Last Stand (Complex)
    - Makes you survive on half a heart from an otherwise-fatal attack.
- [ ] Transmutation Spells
  - [ ] Magentism (Simple)
    - Your aura forms into a magnetic field, pulling entities closer to you.
  - [ ] Ring of Fire (Simple)
    - Your aura forms a ring of fire around you that ignites entities and blocks.
  - [ ] Porcupine (Intricate)
    - Your aura forms into multiple spikes, forming a ball of needles around the player that hurts anyone that gets too close.
  - [ ] Discharge (Intricate)
    - Your aura forms an electrified field around you, stunning entities.
  - [ ] Rejuvinating Presence (Intricate)
    - Heals all nearby entities while active at a rate of 1 hp/second, regardless of allegiance.
  - [ ] Bungee Gum (Complex)
    - When cast, it creates a bubble of aura around the player that catches projectiles. When cast again, it will launch those projectiles in the opposite direction they were caught in.
  - [ ] Suppression Field (Complex)
    - Blocks all magic from being cast in a radius around you. Causes spells that enter it to fizzle out.
- [ ] Emission Spells
  - [ ] Magic Missile (Simple)
    - Launches a weak projectile made of aura.
  - [ ] Chaos Bolt (Simple)
    - Fires a bolt of aura that deals a random damage type to whatever it hits.
  - [ ] Excavate (Intricate)
    - Lobs a projectile that mines large chunks of materials as strong as, or weaker than, stone.
  - [ ] Aura Stream (Intricate)
    - Fires a sustained, piercing beam of pure aura that damages entities.
  - [ ] Healing Orb (Intricate)
    - Fires an orb that, upon making contact with an entity, latches on and heals them for 1 hp every 0.5 seconds for 5 seconds.
  - [ ] Bouncing Charge (Complex)
    - Fires a projectile that bounces off blocks and entities, and targets other nearby entities.
  - [ ] Master Spark (Complex)
    - Haha very powerful rainbow beam go BRRRRRRRR.
- [ ] Conjuration Spells
  - [ ] Arcane Hand (Simple)
    - Summons a magical hand that attacks anything nearby indiscriminently.
  - [ ] Spring Totem (Simple)
    - Creates a totem that will bonemeal nearby plants and heal entities for 1 hp/second.
  - [ ] Black Tentacles (Intricate)
    - Summons a ring of tentacles that will attack anything that gets too close.
  - [ ] Summon Shade (Intricate)
    - Creates a shadow-like entity that attacks anything that interacts with the block it's spawned in.
  - [ ] Black Hole (Complex)
    - Summons a void in space that pulls all entities towards it and deals damage.
  - [ ] Satellite Dragonfly (Complex)
    - Creates a dragongly-like entity that the player can control and see through.
  - [ ] Crazy Slots (Complex)
    - Rolls a number 1-9 and gives the player a random powerful weapon for a few seconds.
- [ ] Manipulation Spells
  - [ ] Pacify (Simple)
    - Temporarily makes hostile mobs neutral.
  - [ ] Arcane Lock (Simple)
    - Locks containers so no one can open them until disspelled.
  - [ ] Telekinesis (Intricate)
    - Allows you to pick up entities and blocks from a distance.
  - [ ] Ward (Intricate)
    - Makes blocks unbreakable until disspelled.
  - [ ] Animate Armour (Complex)
    - Animates armour stands to use whatever weapons and armour they're given.
  - [ ] Turn Ally (Complex)
    - Makes hostile mobs allies, making them fight for you.
- [ ] Specialist Spells
  - [ ] Impersonate (Simple)
    - Take the appearance of another player, including appearing as if you're wearing the same gear that they are wearing.
  - [ ] Arcane Binding (Intricate)
    - Lets you link yourself to another entity, giving you both large buffs but forces you to physically be within a certain distance of each other.
  - [ ] Pocket Dimension (Complex)
    - Creates a portal on the ground/in a wall (either where the caster clicks, or at their feet if no location exists) that lasts for 10 seconds. If an entity walks into/over it, they will enter the pocket dimension.
  - [ ] Thief's Gambit (Complex)
    - Allows the caster to "steal" another player's currently selected spell, locking it from being cast and temporarily replacing this spell with that. Lasts 10 seconds or until the caster dies. Will also cancel a spell's effects if it's currently being cast.
  - [ ] Temporal Disruption (Unique)
    - Slows down time for all entities and block entities in a localised area around the caster.
    - If wearing the North Cultist Leader Robes, it will completely stop time.
  - [ ] Planeswalker (Unique)
    - Places the player on another spacial plane, making the caster unable to interact with other entities.
    - If wearing the South Cultist Leader Robes, the caster can phase through blocks.
  - [ ] Restraint Level Zero (Unique)
    - Makes all other spell casting free for the duration of the spell.
    - If wearing the East Cultist Leader Robes, all spell cooldowns are halved.
  - [ ] Aura Prodigy (Unique)
    - Gain 100% proficiency with all 5 spell categories while active.
    - If wearing the West Cultist Leader Robes, \[TBD\].

## Cults
- [ ] Cults are groups of mages who formed around ancient Gemstone Tablets, tied to certain Specialist spells, making them the only source of these Specialist spells in the world.
- [ ] The player can join up with one, but not all four, of these cults during any given playthrough, though they will learn of any cult's domain before being given the choice of joining. However, joining a cult will make the remaining 3 cults hostile towards the player.
  - [ ] There is one method in which a player can change their allegiance: by summoning a spirit who will strip the player of their memories of the cults, and the cults of their memories of the player.
- [ ] Once the player's reputation is sufficiently high enough with a given cult, that cult will allow the player to learn their unique spell.
- [ ] There are 4 cults that can be interacted with in the world. They are:
  - [ ] **Cult of The North**
    - [ ] Spawns at (x: -512 to 512, z: -3072 to -4096)
    - [ ] Guards a Gemstone Tablet made of Diamond
    - [ ] They are the masters of Temporal Disruption and are the only way to obtain the spell
  - [ ] **Cult of The South**
    - [ ] Spawns at (x: -512 to 512, z: 3072 to 4096)
    - [ ] Guards a Gemstone Tablet made of Quartz
    - [ ] They are the masters of Planeswalker and are the only way to obtain the spell
  - [ ] **Cult of The East**
    - [ ] Spawns at (x: 3072 to 4096, z: -512 to 512)
    - [ ] Guards a Gemstone Tablet made of Amethyst
    - [ ] They are the masters of Restraint Level Zero and are the only way to obtain the spell
  - [ ] **Cult of The West**
    - [ ] Spawns at (x: -3072 to -4096, z: -512 to 512)
    - [ ] Guards a Gemstone Tablet made of Emerald
    - [ ] They are the masters of Aura Prodigy and are the only way to obtain the spell

## Gemstone Tablets
- [ ] Ancient magical artefacts that, when brought together, are able to summon an ancient temple to a god-like being.
  - [ ] Once summoned, the player will be given 3 tasks (difficulty dependant on a global counter) to fulfill within 1 in-game day of being given the tasks. Failure to complete all three tasks will result in a curse that can only be removed via a wish, but succeeding will allow the player to make a wish from a pre-defined list. The more valuable the wish, the harder subsequent tasks become for anyone who casts the spell.
  - <details>
      <summary>List of Tasks</summary>
      <ul>
        <li>
          Wish Counter: 0-24
          <ul>
            <li>Jump</li>
            <li>Kill a pig</li>
            <li>Place an Iron Block</li>
          </ul>
        </li>
        <li>
          Wish Counter: 25-49
          <ul>
            <li>Give me a Blaze Rod</li>
            <li>Take exactly 10 damage in one hit</li>
            <li>Kill a skeleton</li>
          </ul>
        </li>
        <li>
          Wish Counter: 50-74
          <ul>
            <li>Kill an Enderman</li>
            <li>Give me a Diamond Block</li>
            <li>Die in the Nether</li>
          </ul>
        </li>
        <li>
          Wish Counter: 75-100
          <ul>
            <li>Give me a piece of Netherite armour</li>
            <li>Bring me a Wither Skull</li>
            <li>Kill the Ender Dragon</li>
          </ul>
        </li>
      </ul>
    </details>

  - <details>
      <summary>List of Curses</summary>
      If you have a curse, and get the same curse again, it goes up a level. If there are no curses above the one you have, you will die, lose your spawnpoint, lose your entire inventory, and a large explosion will occur where you stand. Have fun~<br>
      <ul>
        <li>
          Wish Counter: 0-24
          <ul>
            <li>Colour Blindness - makes the player see everything in grey-scale.</li>
          </ul>
        </li>
        <li>
          Wish Counter: 25-49
          <ul>
            <li>Brittle Bones - makes the player take 2x damage from all sources.</li>
          </ul>
        </li>
        <li>
          Wish Counter: 50-74
          <ul>
            <li>Klutz - makes the player randomly drop an item in their hotbar.</li>
          </ul>
        </li>
        <li>
          Wish Counter: 75-100
          <ul>
            <li>Aura Seal - Aura Lock is set to 20, preventing the player from casting spells.</li>
          </ul>
        </li>
      </ul>
    </details>

  - <details>
      <summary>List of Wishes</summary>
      <ul>
        <li>Duplicate given item - +20 to counter</li>
        <li>Kill given player - +20 to counter</li>
        <li>Teleport me to given location- +10 to counter</li>
        <li>Cast spell on given player - +5 to counter</li>
        <li>Enchant given item with a selected enchantment - +25 to counter</li>
        <li>Summon given entity - +20 to counter</li>
        <li>???</li>
        <li>???</li>
        <li>Wipe my allegience from my cult - +50 to counter</li>
        <li>Remove all curses from given player - +50 to counter</li>
      </ul>
    </details>
- [ ] Each tablet is held by one of the four cults. The only way to obtain them is to steal them from all four cults, as neither will part with it willingly.
  - [ ] Each tablet is instanced per player, allowing for every player to get a copy of the tablet.
  - [ ] If destroyed, despawned, or stolen, it will appear back in the hands of the cult it belongs to for the player that lost it.
- [ ] There are four tablets:
  - [ ] Diamond Tablet, held by the Cult of The North
  - [ ] Quartz Tablet, held by the Cult of The South
  - [ ] Amethyst Tablet, held by the Cult of The East
  - [ ] Emerald Tablet, held by the Cult of The West

## Origins Compat
- [ ] Players can select the Mage Origin, a human who dedicated their life to the study of magic.
  - [ ] + Starts with 4 spell slots.
  - [ ] + All Aura Types get a 15% bonus.
  - [ ] + Spells cost one less aura.
  - [ ] - Melee weapons deal 50% less damage.
  - [ ] - Non-magical armours give 25% less protection.
- [ ] Players can select their Aura Affinity if they select the Mage Origin.
  - [ ] Gives the Mage a Simple spell from their selected Aura Type of their choosing.
